# checkersautomation
Framework Structure.
     Integration->Examples -  Tests are located in this folder.
     Integration->pageObjects- Where the page object reusable libraries for the methods are located.

Methods:
          navigateUrl() -> Navigates to the URL https://www.gamesforthebrain.com/game/checkers/.
          validatePageisLoaded()-> Validate if the Checkers home page is loaded Successfully.
          restartTheGame()-> Restarts the Game.
          validateTheGameisRestartedSuccessfully()-> Validate Game is restarted is Successfully.
          validateTheMoveConformation()-> Validated if the "Make the new Move" is active.
          makeNextFiveMoves()->make and validate the next 5 moves.

          
Pre-requisites

     Install the Cypress using below command
     npm install cypress --save-dev
     
Run the Tests

   Headed Mode.
     npx cypress run --spec cypress/integration/examples/checkers.js --browser chrome --headed
    Headless on chrome
    npx cypress run --spec cypress/integration/examples/checkers.js --browser chrome
    Command to run the tests to record in DashBoard.
    npx cypress run --record --key 286d2b20-4ba6-4c5b-873d-a80973b5f1ab cypress/integration/examples/checkers.js --browser chrome --headed

DashBoard
https://cloud.cypress.io/projects/4nrhqt/analytics/runs-over-time
