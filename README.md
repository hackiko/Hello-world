/*Starting up*/

var name, git, github;

name = David;
git = workflow;
github = projects;

if(github === projects && git === workflow && name === David) {
Git();
GitHub();
}
else {
error();
}

function Git() {
document.body.innerHTML = "Hello Git";
}

function Github {
document.body.innerHTML = "HELLO GITHUB";
}

function error() {
document.body.innerHTML = "one of the variables did not much";
}
