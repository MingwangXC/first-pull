React is a javaScript libary for building user interface.

  * **Declarative**: React makes it painless to create interactive  Uls. Design simple views for each state in your application，and React will efficiently update and render just the right components when your code more predictable,simpler to understand,and eraier to debug.  
  * **Component-Based**: Build encapsulated components that manage their state,then compose them to make complex Uls,Sine component logic is written in JavaScript instead of templates,you app and keep the state out of the DOM.  
  * **Learn Once**, Write Anywhere：We don't male assumption about the rest of your technology stack,so you can doevelop new features in React can also render on the server using Node and power mobile apps using Node and power mobile apps using [React Native](https://reactnative.dev/). 

  
  [Lear how to use React in projiect](https://reactjs.org/docs/getting-started.html).

  # Installation

  React has been designed for gradual adoption form the start,**and you can use as much React as you need：

  * Use [Online Playgrounds](https://reactjs.org/docs/getting-started.html#online-playgrounds) to get a taste of Reast.   
  * [Add React to a Website](https://reactjs.org/docs/add-react-to-a-website.html) as a tag in one minute.`<script>`
  * [Create a New React App](https://reactjs.org/docs/create-a-new-react-app.html)  if you're looking for a powerful JavaScript toolchain.

  You can use React as a tag from a [CDN](https://reactjs.org/docs/cdn-links.html),or as a `react` package on [npm](https://www.npmjs.com/package/react).

  # Documentation

  You can find the React documentation [on the website](https://reactjs.org/).     

  Check out the [Getting Started](https://reactjs.org/docs/getting-started.html) page for a quick overview.   

  The documentation is divided into several sections:

  * [Tutorial](https://reactjs.org/tutorial/tutorial.html)   
  * [Main Concepts](https://reactjs.org/docs/hello-world.html)   
  * [Advanced Guides](https://reactjs.org/docs/jsx-in-depth.html)   
  * [API Reference](https://reactjs.org/docs/react-api.html)   
  * [Were to Get Support](https://reactjs.org/community/support.html)   
  * [Contributing Guide](https://reactjs.org/docs/how-to-contribute.html)   

  # Examples   

  We have several examples [on the website](https://reactjs.org/).Here is the first one to get you started:   
  ```import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />); 
  ```   
  This example will render "Hello Taylor" into a container on the page.   

  You'll notice that we used an HTML-like syntax;[we call it JSX](https://reactjs.org/docs/introducing-jsx.html). 







  