# homebridge-stateless-switch
This is a plugin for homebridge.
This is a part of a bigger project

## Installation
`sudo npm install -g homebridge-stateless-switch`

## Installation
To use it just use a cofiguration like this:

```
{
  "bridge": {
    "name": "HomeBridge",
    "username": "CC:33:3B:D3:CE:32",
    "port": XXXXX,
    "pin": "XXX-XX-XXX"
  },

  "description": "",

  "accessories": [
    {
      "accessory": "StatelessSwitch",
      "name": "Button Name",
      "onUrl": "UrltoUse"
    },
  ],

  "platforms": []
}
```
