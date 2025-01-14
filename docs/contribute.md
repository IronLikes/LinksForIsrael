---
---
# איך לתרום לפרויקט

---
[עמוד הבית](https://linksforisrael.com/)
[קבוצת הואצאפ שלנו](<https://chat.whatsapp.com/JjD8eijWfDXD10QbM2VyaX>)

## 🚀 Getting Started

1. **Set Up Your Environment**
   - Make sure you have Git and Ruby installed.

2. **Fork the Repository**
   - Go to our [Github Repo](https://github.com/4tals/LinksForIsrael).
   - Click on the `Fork` button at the top right corner. This will create a copy of the repository in your own GitHub account.

3. **Clone the Forked Repository**

   ```bash
   git clone https://github.com/YOUR_USERNAME/LinksForIsrael.git
   cd LinksForIsrael
   ```

4. **(Optional: If you want to run the GitHub Pages project locally) Install Dependencies**
   - Install bundler:

     ```bash
     gem install bundler
     ```

   - Install project dependencies:

     ```bash
     bundle install
     ```

5. **Run Locally**

   ```bash
   bundle exec jekyll serve
   ```

   > ⚠️ **Note**: There is currently an issue with running the project locally. The theme doesn't display as expected. If you can solve this issue, your contribution would be greatly appreciated!

6. **Install Ruby 3**
   Check how to install an up-to-date version of Ruby for your system [here](https://www.ruby-lang.org/en/documentation/installation/).

7. **Install Ruby dependencies**
   Bundler should be installed now as well. Run `bundle install`.

8. **Run the project locally**

   ```bash
   bundle exec jekyll serve
   ```

9. **Run the project locally on a mobile device**
   Make sure your phone is connected to the same network as the server
   Run serve with the `--host` flag:

   ```
   bundle exec jekyll serve --host=0.0.0.0
   ```

   On your mobile device open your server's local IP (you can get it using tools like `ipconfig getifaddr en0`)

## 📖 Understanding the Project Structure

Take some time to understand the layout of the repository. Familiarize yourself with the directory structure, the type of files, and their content.

Then, pick one of the open issues in [*Github Issues*](<https://github.com/users/4tals/projects/1/views/2>)

## 🛠 Making Changes

1. **Create a New Branch**

   ```bash
   git checkout -b my-new-feature
   ```

2. **Find the Appropriate Page/Section**
   - Navigate to the file where you want to add or modify content.

3. **Make Your Changes**
   - Edit the files using your preferred code editor.
   - Remember to follow the project's coding standards and maintain the existing style.

4. **Commit Your Changes**

   ```bash
   git add .
   git commit -m "Added new information about XYZ"
   ```

## 🚀 Submitting Your Contribution

1. **Push to Your Fork**

   ```bash
   git push origin my-new-feature
   ```

2. **Open a Pull Request (PR)**
   - Go to the `Pull requests` tab on the original [Github Repo](https://github.com/4tals/LinksForIsrael).
   - Click `New Pull Request`.
   - Choose the source branch (your branch `my-new-feature`) and the destination branch `main`.
   - Fill in the PR template, explaining your changes.
   - Click `Create Pull Request`.

3. **Await Review**
   - The project maintainers will review your contribution. They might provide feedback or request changes.
   - Once your contribution is approved, it will be merged into the main codebase.

## 🎉 Congratulations

You've just made your first contribution to the ConnectPortal project! Thank you for your help and dedication.
