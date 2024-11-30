```ts
const addToCard = (itemName) => {
    cy.contains('.inventory_item', itemName).within(item => {
      cy.wrap(item)
        .should('not.contain', 'Remove')
        .contains('button', 'Add to cart')
        .click()
    })
  }
```

**get** - ищет теги по селектору (tegs, classes, id, attributs)

**contains** - ищет теги по их названию (не обязательно) и тексту
contains('button', 'Add to cart')

**then** - позволяет работать с обїектам/значением полученнім в результате предеідущей команді. результат нужно оборачивать в cy.wrap, чтобі біло доступнов cypress, так как результат then есть в jQuery 

**invoke** - візівает функцию jqury у тега (index, attr, val)
```
.invoke('attr', 'for')
```