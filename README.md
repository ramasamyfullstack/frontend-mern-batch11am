# frontend-mern-batch11am

# npm install gh-pages --save-dev


# in package.json add,

"homepage": "https://your-username.github.io/frontend-mern-batch11am"


ex,

{
  "name": "frontend-mern-batch11am",
  "version": "0.1.0",
  "private": true,
  "homepage": "https://your-username.github.io/frontend-mern-batch11am",
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.17.0",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
  },
  "devDependencies": {
    "gh-pages": "^5.0.0"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  },
  "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
    ]
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  }
}

Add deploy scripts in package.json:

"scripts": {

  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"

}



in BrowserRouter add basename 
# BrowserRouter basename = "/ramasamyfullstack/frontend-mern-batch11am">
  
  ## Layout />
  
  Routes>    
    Route exact path='/' element={<TraineeList />} />
    Route path='/add' element={<TraineeAdd />} />
    Route path='/update' element={<TraineeUpdate />} />    
  /Routes>
  
# BrowserRouter>

# npm install

# npm run deploy

# npm run build



====================

upload all files from build folder in GitHub

setting -> pages -> change to main in branch -> save



