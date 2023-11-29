# Ecosystem

Live Preview : https://benevolent-faloodeh-fea9f6.netlify.app/

![image](https://github.com/Arafath-21/Ecosystem/assets/111886507/eb4759e2-9d6e-425a-807e-1c0280123a7f)

*____first create a json file with deafult values and install the dependencies according to the need

npm init -y
npm install sass bootstrap font-awesome autoprefixer bootstrap-icons @fortawesome/fontawesome-free --save

*____After instalation of the Dependencies go to the JSON file and change the scripts to the below mentioned:

"scripts": {
    "compile:sass": "sass scss:assets/css"
  },

*____After the script changes create a folder called scss and in that folder create a file called style.css

*____give the command in the Terminal

npm run compile:sass

*____After that command you will be getting a folder called Assets.

*____to have continous check in the sass file, convert the scripts in JSON to below:

"scripts": {
    "compile:sass": "sass --watch scss:assets/css"
  },


