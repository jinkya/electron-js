# electron-js
let's begin our journey for the desktop applications, cheers!


## CLI docs

npm i -g electron-forge 

### import		
				electron-forge import [path]					
				Attempts to import the given module directory to the Electron Forge standard
### init			
				electron-forge init [path]
				--template=[value]			angular2/react/react-typescript/vue			// default ES 6/7 
				--lintstyle=[value]
				Initializes a new application from a basic temnplate

### install		
				electron-forge install [owner]/[repo]
				Installs an Electron application from the given GitHub repository in the form "owner/repo", for example "atom/atom".
				--prerelease				// fetch the latest release with prereleases
### lint 		
				electron-forge lint [path]			by default current path
				Runs the lint task of the application found at "path" and outputs the results if it fails, if it succeeds there will be no output.
### make			
				electron-forge make [path]
				Makes platform specific distributables of your Electron application.
				only generate distributables for your current platform
				--arch=[value]
				--targets=[value]
				--skip-package
### package
				electron-forge package [path]

### publish
				electron-forge publish [path]				[https://electronforge.io/cli/publish]

### start
				electron-forge start [path]
