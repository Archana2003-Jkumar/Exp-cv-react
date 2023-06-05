# Exp-cv-react
## Aim:
To create a CV portfolio using react.
## Code:
```
import './index.css'
import './App.css';
import React from 'react';
import image from './cv.jpg';
import ins from './ins.jpg';

function App(){

 
  return (   
 
<div className="App">
      <header className="App-header">
      <h1>CURRICULAM VITAE</h1>
        <div className="container1">
     
<img src={image} alt='' className='image'/>
        
          <div className='text'>
            <div className="design">Name:J.Archana priya </div>
            <div  className="design">Age : 19 </div>
            <div className="design">Phone number :  123456789</div>
            <div className="design" >Address: Chennai</div>
            <div className="design">Educational Qualification: B.Tech AI-DS</div>
   </div>
      <div className='heading'><u>Programming Skills</u></div>
      <br></br>
     
       <li className='design'>C programming</li>
       <li className='design'>Java proogramming</li>
       <li className='design'>Python programming</li>
   

       <div className='heading2'><u>Education</u></div>
      <br></br>
      
       <li className='design'>SSLC:89%</li>
       <li className='design'>HSLC:92%</li>


       <div className='heading2'><u>Achievements</u></div>
      <br></br>
      
       <li className='design'>Coordinated best event of AI-DS in Drestien2022</li>
      <div className='footer'>
       <div><u>Contact</u></div>
       <img src={ins} alt='' className='image2'/>
       <a href="https://www.instagram.com/achupriya_j/">
        </a>
        </div>
       
       

  </div>
       
      </header>
    </div>
  );
  }

export default App;

```
```
Index.css
```
```
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
    sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

code {
  font-family: source-code-pro, Menlo, Monaco, Consolas, 'Courier New',
    monospace;
}
.button1{
  text-align:center; 
  font-size:25px;
 margin-top: 1cm;
 margin-left: 29cm;
}
.container1{

  width:45cm;
  background-color: rgb(86, 164, 164);
  float:right;
  border-color: black;
  border-radius: 80px;

}
.text{
 text-align: left;
 margin-left: 700px;
 margin-top: 50PX;
}
.design{
  height: 45px;
  font-size: 25px;
  color:black;
 
}
.heading{
  color: rgb(96, 0, 120);
  font-size: 50px;
  text-align: center;
  margin-top: 1cm;
  background-color:rgb(90, 90, 212);
}
.heading2{
  color: rgb(96, 0, 120);
  font-size: 50px;
  text-align: center;
  margin-top: 1cm;
  background-color:rgb(90, 90, 212);
}
.image{
  height: 300px;
  width: 250px;
  float: center;
 margin-top: 1.5cm;
}
.image2{
  height: 90px;
  width: 90px;
  float: center;

}
.footer{
  color: rgb(96, 0, 120);
  margin-bottom: 20px;
  font-size: 50px;
  text-align: center;
}
```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp-cv-react/assets/93427594/3efd9bc0-9868-4e7c-8577-b18ce6e9afde)
## Result:
Hence the code has been successfully completed.
