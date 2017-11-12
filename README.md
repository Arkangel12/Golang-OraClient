

With this dockerfile you'll be able to: <br / >

<ul>
	<li> Connect to Oracle DB with Instant Cliente </li>
	<li> Developing in a flil GoLang Enviroment </ul>
</ul>

<br />

Instruction:

<ul>
	<li> Move to the path where you are going to manage the code as a host (ex. /users/Arkange/data) </li>
	<li> Build your image with (change youruser for your github username) : docker build -t yourimagename --build-arg username=youruser . </li>
	<li> 
		This is the way i run it but feel free to change it if your want to, maybe you want it dettacht (-d) or somethign else <br />
		docker run -it -p 8080:8080 -v "$(pwd)":/work/src/github.com/youruser --name container-name yourimagename
	</li>
	<li></li>
</ul>