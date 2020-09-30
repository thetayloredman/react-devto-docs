# Welcome to the React - Dev.to Documentation!

{% hint style="info" %}
This documentation is still **WIP** \(Work in Progress\).
{% endhint %}

## What is React-Dev.to?

React-Dev.to is a way to embed your Posts on Dev.to into your React Project.

## How do I get started?

{% tabs %}
{% tab title="NPM" %}
First, install the module:

```text
npm install --save react-devdotto
```
{% endtab %}

{% tab title="Yarn" %}
First, install the module:

```text
yarn add react-devdotto
```
{% endtab %}
{% endtabs %}

## Example

```javascript
import DevDotTo from 'react-devdotto'
// username can be found on dev.to
// remove coverimage by adding props 'coverimag={false}', default is true
const App = () => {
  return <DevDotTo username="genialkartik" />
}

export default App
```

