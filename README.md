<h1 align="center"> Simple Flask web app using a secret </h1>
<br/>
<p>In this project I created a small python app the can retrieve a scret from env variable and display adjusted content based on the success of the retrieval.</p>
<p>this ia a sample app to test deployments using pulled secrets being accessed from environment variable <strong>MY_SECRET</strong> </p>
<br/>
<h4>Instructions for Docker: </h4>
<br/>
<ul>
    <li> To run the app run "python3 ./src/app.py"
    <li> The app runs on  port 5000 inside of the container by default use port mapping if needed
    <li> Make sure to not insert your secret during build time
</ul>
