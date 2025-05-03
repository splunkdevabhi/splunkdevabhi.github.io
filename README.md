# Abhishek Shukla - Professional Profile PWA

This is a Progressive Web App (PWA) showcasing the professional profile of Abhishek Shukla, a Senior Engineer specialized in Observability and Security Operations.

## Features

- Responsive design that works on desktop and mobile devices
- Progressive Web App (PWA) functionality for offline access
- Can be installed on devices via browsers that support PWAs
- Clean, professional layout that highlights skills and experience

## Deployment on GitHub Pages

1. Fork or clone this repository
2. Replace `profile.jpg` with your own profile picture
3. Create the following folder structure and add icon files:
   ```
   /icons
     /android-chrome-192x192.png
     /android-chrome-512x512.png
     /apple-touch-icon.png
     /favicon-16x16.png
     /favicon-32x32.png
   ```
4. Add a `favicon.ico` file in the root directory
5. Push the repository to GitHub
6. In your repository settings, enable GitHub Pages:
   - Go to Settings > Pages
   - Select the branch you want to deploy (usually `main` or `master`)
   - Save the settings

Your PWA will be available at `https://[your-username].github.io/[repository-name]/`

## Local Development

To test the PWA locally:

1. Install a simple local server like [http-server](https://www.npmjs.com/package/http-server)
   ```
   npm install -g http-server
   ```

2. Navigate to the project folder and run:
   ```
   http-server
   ```

3. Open your browser and go to `http://localhost:8080`

## Customization

- Edit the HTML and CSS in `index.html` to modify the layout and styling
- Update information in `manifest.json` if needed
- You can add more pages or features as needed

## License

This project is available for personal and professional use.