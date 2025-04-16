# People Repository

Welcome to the People repository for our Hackathon project website! This repository contains a list of participants (people) who are interested taking part in the hackathon and their details.

## How to Contribute

During this session, you'll be making contributions by:

1. **Cloning the repository**: You will first clone this repository to your local machine.
2. **Creating a branch**: You'll create a new branch for your changes.
3. **Making updates**: Update or add your own profile to the `people.json` file with your name, bio, skills, and any other relevant details.
  - Here’s the structure of the data you need to add:
   
   ```json
   {
     "name": "Your Name",
     "bio": "A brief description about yourself.",
     "photo": "URL to your photo",
     "skills": ["Skill 1", "Skill 2", "Skill 3"],
     "interests": ["Interest 1", "Interest 2"],
     "location": "Your Location"
   }
   ```
4. **Creating a pull request**: After making your changes, you'll push your changes and open a pull request.
5. **Resolving merge conflicts**: You’ll also practice resolving any merge conflicts that may arise if there are changes from others.

## File Structure

- `db.json`: Contains an array of participants with their details.
  
## Usage 

This JSON is used to power [we-lead-cs-hackathon.github.io](https://we-lead-cs-hackathon.github.io/). The website pulls data from two separate JSON files hosted on Github using My JSON Server, a fake online REST server for teams. This data is used to display participant profiles and project details on the website.

- The People data is served from the [People JSON Repository](https://github.com/sierraobryan/we-lead-cs-people) (this repository).
- The Projects data is served from the [Projects JSON Repository](https://github.com/sierraobryan/we-lead-cs-projects).
- The [Website Repository](https://github.com/we-lead-cs-hackathon/we-lead-cs-hackathon.github.io) contains the core files for the website (HTML, CSS, JavaScript) and handles the display of the data.

---

**Enjoy contributing, and feel free to explore other issues after the session to continue learning Git!**

Happy hacking!
