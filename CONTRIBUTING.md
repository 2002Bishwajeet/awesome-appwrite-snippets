# Contributing

![algo girl](.github/images/contributing.jpg)

We would ❤️ for you to contribute to this Awesome Appwrite Snippets Project and help make it better! We want contributing to this repo to be fun, enjoyable, and educational for anyone and everyone. All contributions are welcome, including issues, doc improvements as well as updates and tweaks.

## How to Start?

If you are worried or don’t know where to start, check out our next section explaining what kind of help we could use and where can you get involved. You can reach out with questions to [Bishwajeet Parhi (@biswa_20p)](https://twitter.com/biswa_20p) on Twitter or join the [Appwrite Discord Server](https://discord.gg/es7NYxsrR9) and you can ask there. You can also submit an issue, and a maintainer can guide you!

## Code of Conduct

Help us keep Awesome Appwrite Snippets Project open and inclusive. Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

### Installing Locally

Fork the repository. Make sure you have Node.js (LTS version) installed.

```bash
git clone <your-forked-repo>

cd <your-forked-repo>

npm install # Install the dependencies

code . # Open the project in your code editor

```

### Creating a Pull Request

```bash
git checkout -b <new-branch-name>
# Fix some code...

git commit -m "Fix typo in README.md"

git push origin <new-branch-name>

```

The commit naming follows [this structure](https://cbea.ms/git-commit/)

### To add new snippets

1. Create a new file in the `snippets` directory of the format `<name>.code-snippets`. If the name convention exists already, just add them in that file.
2. To add a new snippet, replace the following skeletion code.

```jsonc

    "snippetName": {
        "scope" : "<lang>", // Add the language scope here. For e.g `dart`
        "prefix" : "<suitable-prefix-name>", // Add the prefix which tells vscode that this snippet is being called
        "body" : "<snippet-body>", // Add the snippet body here.
        "description": "<snippet-description>" // Add the snippet description here.
    }
```
Follow this [page](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets) to create snippet body.

3. If you created a new file, declare its language scope and path in the `package.json` under `snippets` array.

```jsonc
"contributes": {
    "snippets": [
        // ... more snippets
      {
        "language": "language",
        "path": "./snippets/path-to-snippets"
      },
    ]
}

```

4. Once added don't forget to test it locally. Press `F5` to debug. It will open a new vscode window and try testing your snippets in the files.

5. Once tested, commit changes, push to the repository and open a pull request.

## Other Ways to Help

Pull requests are great, but there are many other areas where you can help on this Project.

### Sending Feedbacks & Reporting Bugs

Sending feedback is a great way for us to know how do you liked this project. If you had any issues, bugs, or want to share about your experience, feel free to do so on our GitHub issues page.

### Improving Documentation

Submitting documentation updates, enhancements, designs, or bug fixes. Spelling or grammar fixes will be very much appreciated.

### Showcasing

You can also give a shoutout to this project on your blog, website, or in you social handles tagging [Bishwajeet Parhi (@biswa_20p)](https://twitter.com/biswa_20p) and demonstrating the use of the snippets in your appwrite projects.
