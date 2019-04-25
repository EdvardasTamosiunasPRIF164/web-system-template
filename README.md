# WEB system
- [ ] COIN TRACKER powered by CoinLayer

## Description
- [ ] Provides information about selected crypto coin live price, shows the list of added crypto coins
and their live prices

## COIN WATCHLIST
- [ ] ID: WATCHLIST ID, mandatory (number, 0 < ID < 100 characters)
- [ ] Symbols: Coin symbol, mandatory (Number 0 < symbols < 4 characters)
- [ ] Name: CoinName, mandatory (String < 100 characters)
- [ ] TimeStamp: Time stamp when info was received, mandatory (number < 11 characters)
- [ ] Target: Live price USD, mandatory (number < 8 chars)
- [ ] PriceBTC: Live price BTC, mandatory (number < 8 chars)
- [ ] Cap: Coin cap rate, mandatory (number < 100 chars)
- [ ] vol: Coin volume rate, mandatory (number < 100 chars)

## API definition
- [ ] Get live coin price, by it's symbol. Method Get, /live/symbols | possible error 404 (not found)
- [ ] Create a coin watchlist. Method POST, /live/{id} | error code 202 (Invalid currency simbols)
- [ ] add a coin to the watchlist. Method PUT, /live/{id} | error code 202 (Invalid currency simbols)
- [ ] Change target currencies, Method PUT, /list | error code 404 | error code 202 (Invalid currency simbols)
- [ ] Delete a coin from the watchlist. Method DELETE, /list/{id} | error code 404, 202 (Invalid currency simbols)

## UI definition
- [ ] TWO PAGES:

- [ ] First page:
        Search for a coin,
      - [ ] new: search for a crypto coin,
      - [ ] Target: specify target coin currency,
      - [ ]  Add: Add a coin to the watchlist.
       
- [ ] Second page:
  coin watchlists,
  - [ ] Create: Create a watchlist,
  - [ ] Search: add a new coin to the watchlist,
  - [ ] Edit: Specify target currency for a specified coin,
  - [ ] Edit: Edit watchlist (delete coins from the list),
  - [ ] Delete: Delete a coin from the watchlist
  
  
link to wireframe second page view: https://wireframe.cc/aJgOGr
