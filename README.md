# Awesome Appwrite Snippets

Awesome Appwrite Snippets is a collection of commonly used Appwrite APIs. It increases your speed of development by eliminating most of the boilerplate code associated with making using Appwrite in your Project.

![example](https://github.com/2002Bishwajeet/awesome-appwrite-snippets/blob/7477e42f2a7a53840863d0779b2b3270720d139e/.github/images/appwrite.gif)

## Features

- Speeds up development
- Eliminates boilerplate

|          Shortcut           | Description                                   |
| :-------------------------: | --------------------------------------------- |
|          `client`           | Create a Client and initialize it             |
|        `dartclient`         | Create a Dart Client object and initialize it |
|          `account`          | Create an Account object and initialize it    |
|         `crAccount`         | Create a new Account                          |
|   `createAccountSession`    | Create a new Account Session                  |
|      `crsessionOAuth2`      | Create a new Account Session with OAuth2      |
|         `magicUrl`          | Create a new account session with Magic Url   |
|      `updatemagicUrl`       | Update Magic URL session                      |
|  `createAnonymousSession`   | Create a new Anonymous Session                |
|          `storage`          | Create a Storage object and initialize it.    |
|        `createFile`         | Create a new file.                            |
|        `updateFile`         | Update a file by its unique ID.               |
|         `document`          | Create a Document object and initialize it.   |
|      `createDocument`       | Create a new Document.                        |
|      `updateDocument`       | Update a document by its unique ID.           |
|           `team`            | Create a Team object and initialize it.       |
|     `crTeamMembership`      | Create a new Team Membership.                 |
| `updateTeamMembershiproles` | Update a team membership by its unique ID.    |

## Known Issues

At this time, there are no known issues. If you discover a bug or would like to see a shortcut added, please create a pull request at our GitHub page.

## Contributing

Contributions are highly Welcomed 💙 . Feel free to open PRs for small issues such as typos. For large issues or features, please open an issue or create a discussion first.

### How to do it

Fork the repository and create a new branch.

```bash
git clone <your-forked-repo>

git checkout -b <new-branch-name>
# Fix some code...

git commit -m "Fix typo in README.md"

git push origin <new-branch-name>

```

The commit naming follows [this structure](https://cbea.ms/git-commit/)

###To add new snippets

1. Create a new file in the `snippets` directory of the format `<name>.code-snippets`. If the name convention exists already, just add them in that file.
2. To add a new snippet, replace the following skeletion code.

```json

    "snippetName": {
        "scope" : "<lang>", // Add the language scope here. For e.g `dart`
        "prefix" : "<suitable-prefix-name>", // Add the prefix which tells vscode that this snippet is being called
        "body" : "<snippet-body>", // Add the snippet body here.
        "description": "<snippet-description>" // Add the snippet description here.
    }
```

Follow this [page](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets) to create snippet body.

## Roadmap

[ ] Add Snippets for more languages
[ ] Cover more Appwrite APIs and convert them to snippets
