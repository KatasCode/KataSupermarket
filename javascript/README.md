# Using Mocks with Jasmine

[Jasmine Spy documentation](http://jasmine.github.io/2.0/introduction.html#section-Spies)

```javascript
describe("A spy", function() {
  var supermarket;

  beforeEach(function() {
    supermarket = new SuperMarket();
  });

  it("tracks that the spy was called", function() {
    spyOn(SupplementMarketInterface.prototype, 'getTax').and.returnValue(11);
  });
});
```
