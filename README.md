Yozu React Skeleton
This project aims to be a base for React Projects at Yozu. This should set up all basic requirements to get a React App up and running, without much need for change from a developer's side.

Using this skeleton
To use this skeleton for a new react app.

Firstly, Clone the skeleton git clone git@bitbucket.org:vpcltd/react-skeleton.git SOME-PROJECT-NAME, changing SOME-PROJECT-NAME to the name of the project you want. Then you can enter that project cd SOME-PROJECT-NAME. This will still be set up to look at react-skeleton.git as the remote origin, so remove it using git remote remove origin. Now that this is done we can make it push to your intended location.

If you havent already, create a Repository in BitBucket, making sure that you do NOT include a README or gitignore as these will be added by the skeleton. Below is an example of what the create repo would look like.

example repo creation

Once a repo has been created, setup the remote using git remote add origin <REPO_URL>.

Finally, once this is done you can push the skeleton to bitbucket, through the normal process of git add ., git commit, git push -u origin main.

Removing Skeleton Info
Since this is a skeleton application, there is some prefilled information that will need to be changed to fit your application.

Package.json: name should be changed to match your project
Manifest.json: Update names and icons to match your project
public/ : Change favicon and logoXXX images
create-repo.png
README - replace with app specific instructions
Running the Application
To run this application there are a few requirements:

Node v20
Yarn
Docker
Once cloned, run the following to get the app started

yarn install
yarn start
Open a web browser of choice
Go to http://localhost:3000
You should now see the Skeleton application running on your browser
