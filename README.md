# Personal Website
## Checklist
- WireFrames
- Github Repo- 10commits
- Colour Scheme/Font
- Install Bootstrap
- Link Custom stylesheet
- Build HTML Template
- Start Bootstrapping/CSSing

##### Deadline: 2pm 3rd Aug 2017
##### Must be Responsive!
## Readme Contents
 - [Website Choice](#website-choice) 
 - [WireFrames](#wireframes) 
     - [Mobile](#mobile)
     - [Desktop](#dekstop)
 -  [Website Creation](#website-creation)


## Website Choice
For my website, I decided to create a website based on myself which would display certain things about me including a gallery and a unique way of showing my hobbies. I have chosen this approach for my first website because it alllows me to display my personality in an interactive way. The fact that it will be responsive also allows mobile users to view my website in a suitable format. 

## WireFrames 
Before developing my website, it was important to create wireframes for both **mobile** and **desktop** formats so that I am able to visualise and come up with the structure of my web application before diving into the code without knowing what to create. This is an important step of the web development process because as well as the developer benefitting from visualising the structure, it also allows the developer to present their wireframes to clients in an excellent manner. 

### Mobile: 
![alt text](https://raw.githubusercontent.com/divesh987/personalWebsite/master/mobileWireframe.jpg "Logo Title Text 1")

## Desktop: 
![alt text](https://raw.githubusercontent.com/divesh987/personalWebsite/master/desktopWireframe.jpg "Logo Title Text 1")

The website was developed with the wireframes in mind however upon completing the wireframe strucutre, I decided to add more content to the website which is why the finished product has more than what the wireframe shows. 

##Website Creation 
The structure of the webpage was created easily using Bootstrap components. 
The main component used of Bootstrap is the grid system which divided the window into 12 equal sections from which the developer can decide to structure the content.

Here is the code used for the first text and form that was structured using the grid system : 
```
<div class="row">
		<div class="col-xs-12 col-sm-12 col-md-6 col-lg-6">
  			<h2>Who is Divesh?</h2>
  			<div class="panel panel-default">
    			<div class="panel-body">
    				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
    				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    				consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
    				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    			</div>
  			</div>
		</div>
		<div class="col-xs-12 col-sm-12 col-md-6 col-lg-6">
  			<h2>Contact Me</h2>
  			<div class="panel panel-default">
    			<div class="panel-body">
    				<form>
  						<div class="form-group">
    						<label for="Email1">Email address</label>
    						<input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    						<small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  						</div>
  						<div class="form-group">
    						<label for="Sujbect">Subject</label>
    						<input type="text" class="form-control" id="text" placeholder="Subject">
  						</div>
  						<div class="form-group">
    						<label for="message">Message</label>
   							<textarea class="form-control" id="exampleTextarea" rows="3"></textarea>
 						</div>
  						<button type="submit" class="btn btn-primary">Submit</button>
					</form>
				</div>
  			</div>
		</div>
	</div> ```

