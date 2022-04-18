<center>

# Face Liveness Detection (Anti-Spoofing) Web App


### A Streamlit WebRTC web app that determines if the person appearing in front of web cam is real and not a photo or a video of someone/something.

</center>

<center>
    <h2> Inspiration </h2>

https://github.com/jomariya23156/face-recognition-with-liveness-web-login

I would highly suggest all of you to take a look at this wonderful project which served as the inspiration for my project.jomariya23156 has also beautifully incorporated face-recognition into his app which has been omitted in my project.

	<h2> Drawback </h2>
	
The drawback of the above mentioned project is that although it claims to be a web app it cannot be used in a server-client scenario as it lacks webrtc features.

For more info, please check out this link:
https://blog.streamlit.io/how-to-build-the-streamlit-webrtc-component/

</center>
<hr>

## ✨ Features

- calculates real and fake ratios
- uses Streamlit's WebRTC features
<hr>

## :rocket: Quick start

Start developing locally.

### Step 1: Clone the repo

Fork the repository. then clone the repo locally by doing -

```sh
git clone https://github.com/abhisheknaiidu/iiitdmj-gpa.git
```

### Step 2: create a virtual environment and activate it. Note: I have used pip

```sh
pip install virtualenv
python -m venv [env-name]
[env-name]\Scripts\activate 
```

### Step 3: cd into the directory

```sh
cd iiitdmj-gpa
```

# install dependencies

```sh
pip install -r requirements.txt
```
 
# And you are good to go
```sh
streamlit run app.py
```
You should now have the application running and accessible at http://localhost:8501.


### Step 4: Deploy and enjoy!

You could deploy the app to cloud platforms such as Streamlit-sharing and Heroku.

Deployment links:
- https://blog.jcharistech.com/2019/10/24/how-to-deploy-your-streamlit-apps-to-heroku/#:~:text=%20How%20to%20Deploy%20Your%20Streamlit%20Apps%20to,CLI.%20%20...%20The%20yourappname%20is...%20More%20
- https://towardsdatascience.com/deploying-a-basic-streamlit-app-ceadae286fd0#:~:text=To%20deploy%20the%20app%20to%20Streamlit%20Sharing%2C%20we,the%20screenshot%20of%20the%20deployment%20page%20on%20streamlit.io.

If you are facing issues with deploying the app remotely, please refer to this link:
https://docs.streamlit.io/knowledge-base/deploy/remote-start


### Sample Output

![Alt Image text](/test_pics/normal.png?raw=true "Normal")

![Alt Image text](/test_pics/with_pic.jpeg?raw=true "With picture")

![Alt Image text](/test_pics/with_video.png?raw=true "With video")



## :v: Contributing

After cloning & setting up the local project you can push the changes to your github fork and make a pull request.


### Pushing the changes

```bash
git add .
git commit -m "feat: added new stuff"
git push YOUR_REPO_URL develop
```

Made by: Sudeep Birudavolu