## SET UP:
To get started, clone this repo


And then:
```
npm install
npm run start
```

API docs can be found [here](https://bitbucket.org/kangpeinc/front-dev-interview/src/master/doc/API.md)

## Instructions:
The tasks below try to simulate a real-life work flow as a frontend developer, focusing on using React as your major tool. Judgement will be made not solely on completion of the tasks, but also other factors such as: Knowledge of fundamental javascript concepts, code refactoring and optimization, use of best practices etc.

PLEASE NOTE: You're not to use any external libraries, other than the ones already provided.

Estimated completion time for tasks is about 4 hours. But I'm sure you can do it in less ;)

### Task 1 (JSON Search):
Write a function that searches through the input array / object
and returns the appropriate string path leading to the input query, if found.
Reference: `/utils/utils.js`

### Task 2 (Client Side Filter):
Add functionality to the input field, such that any input provided, filters the available providers based on their Name, address or Type. 
Hint: The JSON search function you wrote earlier should come in handy here.
Reference: `/layouts/ExplorePage.jsx`

### Task 3 (Component):
#### TASK 3a:
Complete the Gallery component to include functionality
On click on left or right arrows, the gallery should change its image
On click of the thumbnails, the image selected should be updated as well
On click of the "Read more" button in the selected Image, it should redirect to the Selected Provider View.

Heres what it should look like when you're done:
![alt text](https://bitbucket.org/kangpeinc/front-dev-interview-2/src/master/src/gallery.gif "Gallery Component")



#### Task 3b:
Write tests for the Gallery component. Tests should be written in the Gallery.spec.js file in the __tests__ folder.
Reference: `/components/ProviderGallery.js`

### Task 4 (Component):
On the Explore Page, onClick of a view preference, write functionality to all switching across the different view options (Gallery, List, Grid) based on whatever the user selects.
Reference: `/layouts/ExplorePage.jsx`

### Task 5 (Form Submission)
Complete the NewProviderForm to allow creation of new Providers.
Reference:
`/components/forms/NewProviderForm.jsx`

### Task 6 (View Provider)
Add functionality in all places necessary to navigate to a new route for viewing a selected provider.
Use existing styles, or add new ones if you want to :)
Reference:
`/layouts/ViewProvider.jsx`


### All Done?
Awesome! Feel free to improve and optimize the codebase however you like. Ensure you mention whatever optimization you made in the submission mail though, along with the thought process behind it as well.

## Submission
Once done, upload your submission to your Github repo, and send an email to [mayaki@reliancehmo.com]().

Best of luck! :v:
