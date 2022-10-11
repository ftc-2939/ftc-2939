- 👋 Hi, I’m @ftc-2939
- 🌱 I’ve been created by @j-calvert to be used on a shared laptop for programming the robot for team FTC-2939's entry in FTC Powerplay 2022

## Software Development Environment Setup

Here are the steps to set up a development environment
- Get a laptop.  
  As of this writing, I have one called DESKTOP-TKMD55DT that I'm using for this team.
- Install Android Studio, choose defaults for everything
- Install Git
  Assuming windows, and lot's of things to choose: Choose all the default options, except editor used for commits (choose wordpad for that)
- Install Github Desktop
- Create Github user
  This is the account of the user I created for this team
- Create a Git repository on Github for this user and this year's competition
  E.g. [ftc-2939/powerplay-2022](https://github.com/ftc-2939/powerplay-2022)
- Clone [FIRST-Tech-Challenge/FtcRobotController](https://github.com/FIRST-Tech-Challenge/FtcRobotController) into that project by doing the following:
  - Create the directory to use for development.  I've chosen `C:\Users\XbotRobotics\FTC\FtcRobotController`
  - From that directory, run the following:
    - `git clone https://github.com/FIRST-Tech-Challenge/FtcRobotController.git`
      Clones the SDK source to a local repo
    - `git remote add team_repo https://github.com/ftc-2939/powerplay-2022.git`
      Adds our own github repo as a remote
    - `git add .`
      Adds the cloned source to the local repo
    - `git push -u team_repo`
      Pushes the cloned source to *our* remote, and `-u` sets this remote as the primary
  - In Github Desktop, set our remote as the primary and create a branch from the 8.0 tag used for the release of the SDK
    I'm still on the fence about whether or not Github Desktop makes life easier.
- Open this project in Android Studio (the source contains the metadata files that define an Android Studio project).

- Lastly, to allow for remote access to the laptop (for mentoring remotely), install TeamViewer
- And to allow for easy remote video/voice, created google account ftc2939team@gmail.com

This concludes the setup of the environment itself.

Project-specific steps from here on are will be documented in the README.md at https://github.com/ftc-2939/powerplay-2022/tree/v8_branch/TeamCode

