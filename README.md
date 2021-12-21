Design System by Synerise
=

Requirements
==

    node -v
    # >= 12

    npm -v
    # >=6

additional requirements:

  * `react-scripts@3.4.1`
  * preferred `yarn@1.19.0` (`npm install -g yarn@1.19.0`)

newer versions of these packages might work, but if you encounter a problem - try these

Installation
==

<a href="#" click="[...document.querySelectorAll('.yarn')].map(e => e.style.display='none')">use npm</a> |
<a href="#" click="[...document.querySelectorAll('.npm')].map(e => e.style.display='none')">use yarn</a>

<pre class="npm">
  npx create-react-app@3.4.1 ds-boilerplate --template typescript --use-npm
  npm install @synerise/ds-core
</pre>

<pre class="yarn">
  npx yarn@1.19 create-react-app@3.4.1 ds-boilerplate --template typescript --use-yarn
  yarn install
  yarn add @synerise/ds-core
  yarn add @synerise/ds-app-menu
</pre>

Dev
==

    yarn start

Build
==

    yarn build

Deploy
==

    yarn build; yarn deploy
