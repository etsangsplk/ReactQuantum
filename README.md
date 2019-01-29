<p align="center">
  <img width="390" height="134" src="https://user-images.githubusercontent.com/35183001/51876992-720b6180-2338-11e9-9d85-faa80c1e4572.png">
</p>
<h4 align="center">Visualize your React application's component performance metrics in the form of a live heat map.</h4>
<p align="center">
<img src="https://img.shields.io/badge/release-beta-yellow.svg">
 <p>

___

<h2>What It Does</h2>
<p>React Quantum parses through your React application to create a color-coded tree representation of its component hierarchy. On hover, each tree node will display two key component performance metrics&mdash;render time and re-render frequency&mdash;as well as memoized state and props for added context. 

The beauty is in the heat map: Nodes will change color depending on the component's rendering speed, making it easy to pinpoint possible bottlenecks at a glance. :fire:</p>

<h2>How To Get It</h2>
<p>Quantum will soon be available as an extension through the Google Chrome Web Store! 
In the meantime, local setup instructions are as follows:</p>

**NOTE: React Quantum works best for React v16+ local projects in development environments.**

1. `$ git clone https://github.com/ReactQuantum/ReactQuantum.git`

2. `$ cd ReactQuantum`

3. `$ npm install`

4. `$ npm run build-dev`

5. Visit chrome://extensions/

6. Click the Load Unpacked button, then select your './ReactQuantum/build' directory

7. Open Chrome Developer Tools (Inspect) on any page that uses React, then click on the React Quantum panel

8. Click the Start Quantum button, refresh the page

9. Optimize components!

<h2>Definitions</h2>

| Term | Definition |
| --- | --- |
| Render | When a component is painted on the DOM |
| Total render time | Total time a component took to render, including its children |
| Individual render time | Total time an individual component took to render |
| Memoized state and props | The state and props before the component re-rendered |

