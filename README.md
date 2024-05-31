# Minimal and sketch themed personal website
Link to the portfolio: https://tanishabisht.github.io/portfolio-template-2/

![Portfolio template - sketch theme](demo/demo.gif)

## Who is this portfolio website for?
This portfolio is ideal for graphic designers, illustrators or developers who favor a classic, monochrome, sketchy-comicy aesthetic. 

### Style of the Website
The "Classic Sketch" theme embraces a comic feel with a monochrome, black and white sketchy, funky theme. It incorporates funky pattern designs that give the site a dynamic and engaging visual appeal.

### Font Choice: Montserrat
Chosen for its versatility and modern flair, Montserrat complements the black and white theme by offering clean readability and a contemporary edge that aligns well with the sketchy and artistic nature of the website.

### Color Choices
Black (#000000) and White (#FFFFFF). The stark contrast between black and white not only enhances readability but also mirrors the classic sketchbook appearance, providing a perfect backdrop for showcasing graphic artwork.

## How to Customize and Deploy Your Project

### Step 1: Fork the Repository
Begin by forking the repository to create a personal copy under your GitHub account.

### Step 2: Clone Your Fork
Clone the forked repository to your local machine. Replace `(username)` with your GitHub username and `(newreponame)` with the name of the repository.
```bash
git clone git@github.com:(username)/(newreponame).git
```

### Step 3: Set Up Your Project
Navigate to the project directory:
```bash
cd (newreponame)
```

Switch to the appropriate Node.js version using nvm:
```bash
nvm install v16.20.2
nvm use v16.20.2
```

### Step 4: Install Dependencies
Install the necessary project dependencies:
```bash
npm install
```

### Step 5: Start the Development Server
Launch the development server which will host the project on your local machine:
```bash
npm start
```
- The server will be accessible at `localhost:3000`.

### Step 6: Customize Your Project
Make necessary changes to personalize the project:
- Modify the content in the website by editing the variables in the file located at [variables.js](/src/Content/variables.js).
- Update the project images by accessing the folder [here](/src/Images/ProjectImgs/).

### Step 7: Update Repository Configuration
Change the repository URL in [package.json](/package.json) to match your GitHub Pages URL:
```json
"https://(username).github.io/(newreponame)"
```
Replace `(username)` with your GitHub username and `(newreponame)` with your repository name.

### Step 8: Deploy Your Changes
Deploy your updated website to GitHub Pages:
```bash
npm run deploy
```

### Step 9: Configure GitHub Pages
- Navigate to your repository on GitHub.
- Go to `Settings` > `Pages`.
- Set the GitHub Pages source to deploy from the `gh-pages` branch and select the `/(root)` folder.
- Click `Save`.

### Step 10: Access Your Deployed Site
- Your website will be available shortly after deployment.
- Access it via `https://(username).github.io/(newreponame)`.

Follow these steps to customize and deploy your project effectively on GitHub Pages, ensuring it reflects your personal style and preferences.

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.