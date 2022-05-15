# Edvora-Rides-main
Edvora-Task
This is react app simulate rides it have main parts : Neartest , Upcoming , Past

Neartest

A nearest ride is a ride that includes your station code or a number closest to your station code in the station_path array. For example, your station code is 40.
So any ride that has your station code as nearest number in station_path array.
![image](https://user-images.githubusercontent.com/100836959/168487729-294ddcb2-54db-4823-8cc8-f08612538581.png)


filter

Every ride has state and city. You need to get state and city from every ride object and create a list of state & city for the filters dropdown. State : It shows rides from that state only. City: It shows rides from selected city only. If a state is already selected then the city dropdown will have cities from selected state only.


Upcoming

It shows all rides which has date in future.
![image](https://user-images.githubusercontent.com/100836959/168487680-13ff2d55-c467-434f-9493-5f1ecb538933.png)


Neartest

It shows all rides which has date in Past. which mean you can track you roads where to go
![image](https://user-images.githubusercontent.com/100836959/168487672-2f8863aa-779a-4f88-adfd-049540fbc23b.png)


in the project directory, you can run:

npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

npm test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!


