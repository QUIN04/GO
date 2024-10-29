#Portfolio project

11/10/2024
- Read through Angular documentation: https://next.angular.dev
- Install Angular globally, switch my nodejs version and created the portfolio project: https://www.youtube.com/watch?v=GBt031nQPu0
  *npm install -g @angular/cli
  *npm use 20.15.0
  *ng new portfolio-app
  *ng serve
  *ng s -o
- Next step was to create components which were to be built
  *ng g c components/navbar
  *ng g c pages/home
- Next of was to ensure routing accross the different pages set-up with the previous step, I realised that tha app.routes.ts is very import here: https://www.youtube.com/watch?v=dT3f0KTdNyA
  
22/10/2024
!!SKIPPED FOR 11 DAYS, FIGHTING THE STRONGEST BUGS, I'VE FACED SINCE GENESIS😂😂, OMG QUINUELLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL
- Ensured proper routing of the 4 portions of the screen view, Also installed Bootstrap and added it to the package.json file
  *npm install bootstrap

29/10/2024
- Today, I fixed the routing properly for the layout and pages component. Biggest lesson learnt was ensuring to follow same normenclature of files while adding to the app.modules.ts and app.routes files, also cleaning and rebuilding helps too
  *ng clean
  *ng build
- So basically each component created is provided in a folder contain 4 files endiing with the following extensions: .html, .css, .ts, spec.ts
- Basic HTML and CSS on the respective pages plus Bootstrap which wasn't verify successful
- Header, Footer, Navber and Home done
