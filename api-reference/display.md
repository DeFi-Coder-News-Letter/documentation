# Display

## showWallet

Pops up the Torus Wallet app for the user to view. This method is synchronous

```javascript
torus.showWallet(path);
```

**Parameters**

* `path` - `enum` : The route of torus website to open in the popup. Supported options are `transfer` `topup` `home` `settings` `history`

**Examples**

```javascript
torus.showWallet(); // default: 'home'
```

```javascript
torus.showWallet("transfer"); // default: 'home'
```

## showTorusButton

Shows the Torus Button to the user. This method is synchronous

**Examples**

```javascript
torus.showTorusButton();
```

## hideTorusButton

Hides the Torus default button from the user

**Examples**

```javascript
torus.hideTorusButton();
```
