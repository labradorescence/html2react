# html2react

1. App.js 
remove all the logo content between the <div className="App"> and </div>

2. copy the html and paste in the App.js where the logo was located.

3. change `class` to `className`

4. close all the opened elements. 

5. style to styles

6. `styles="enable-background:new 0 0 150 118;"` =>
     `style={{enableBackground:'new 0 0 150 118';}}`
     
     (1) camelCase enable-background => enableBackground
     (2) "" => {{}}
     (3) make it string 
      
7.  `<img src="assets/img/work-metiew-smith.jpg" alt="Metiew and Smith"></img>`
=>
`<img src={require("./img/work-metiew-smith.jpg")} alt="Metiew and Smith"></img>`
