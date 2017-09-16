# The Gold Loop Website

Official Website of The Gold Loop

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1. Command-line Interface

    - For Windows, suggest to use [Cmder](http://cmder.net/).
    - For Mac, suggest to use [iTerm2](https://www.iterm2.com/).

2. Git - [Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

    - May skip this step if will use [Cmder](http://cmder.net/) for Windows. Git is included by default. 

3. Git Configuration

    ```
    ### Open the installed command-line interface and run the
    ### commands below. Please note of the OS-specific configuration.

    ## General Settings
    $ git config --global user.name "John Doe"
    $ git config --global user.email "github@email.com"
    $ git config --global push.default simple
    $ git config --global fetch.prune true

    ## Windows-specific Settings
    $ git config --global core.autocrlf true

    ## Mac / Linux-specific Settings
    $ git config --global core.autocrlf input
    ```

4. Ruby - [Installation Guide](https://www.ruby-lang.org/en/documentation/installation/)
5. Jekyll - [Installation Guide](https://jekyllrb.com/docs/installation/)

    ```
    ### Open the installed command-line interface and run the commands below.
    $ gem install jekyll bundler

    ## Check if Jekyll is installed
    $ jekyll -v 

    ## Go to any temporary directory and create a new Jekyll project.
    ## Note: This step will be executed in order to install Jekyll-related Gems.
    $ cd <some directory>
    $ jekyll new <project name>
    $ cd <project name>

    ## This will build the default static website and may view it at http://localhost:4000
    $ jekyll serve

    ## Note: May delete the project created once done experimenting.
    ```

6. Text Editor / IDE

    - Any editors will do but suggest to try out [Visual Studio Code](https://code.visualstudio.com/) for coding and creating Markdown contents.

        - VSC Extension Recommendations:
        - https://github.com/viatsko/awesome-vscode
        - http://www.hongkiat.com/blog/visual-studio-code-extensions/
        - https://stackify.com/top-visual-studio-code-extensions/
        - https://tutorialzine.com/2017/06/15-essential-plugins-for-visual-studio-code

### Installing

A step by step series of examples that tell you have to get a development env running

Clone the GitHub Project

```
$ cd <desired workspace directory>
$ git clone https://github.com/thegoldloop/thegoldloop.github.io.git
```

Go to the project directory

```
$ cd thegoldloop.github.io
```

Run the Jekyll server

```
$ jekyll serve --watch

## Note: the `watch` flag checks for file changes and rebuilds the site automatically.
## But, when changing the `_config.yml` file, there's a need to restart Jekyll.
```

May now open the web browser and go to http://localhost:4000 to view the website.

## Project Structure

Please read Jekyll's [Directory Structure](https://jekyllrb.com/docs/structure) for detailed directory structure reference.

```bash
├── _drafts
├── _includes
│   ├── disqus_comments.html
│   ├── footer.html
│   ├── google-analytics.html
│   ├── head.html
│   ├── header.html
│   ├── script.html
├── _layouts
│   ├── default.html
│   └── home.html
├── _posts
├── _config.yml
├── .gitignore
├── 404.html
├── CNAME
├── index.md
├── LICENSE
└── README.md
```

TODO: Detailed file descriptions.

## Submitting Project Modifications

Open command-line interface and check for modifications

```
$ cd <project directory>
$ git status
```

Add the modified files that are expected to be committed

```
$ git add folder/folder/file.extension
$ git add file.extension

## Check that the files are already added to staging.
$ git status
```

Commit the staged files.

```
$ git commit -m "This is a sample commit message."

## Note: Always remember that `git commit` only commits to your local Git repository.
```

Once commited, may now push the changes.

```
$ git push
```

TODO: Stricter dev procedure once blog is more stable.

## Deployment

Upon pushing changes to GitHub via the `master` branch, GitHub will automatically publish the changes and update the website.

## Built With

* [UIKit](http://getuikit.com) - The CSS framework used

## Contributing

Currently, the project is not open for accepting pull requests except for the project team members.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/thegoldloop/thegoldloop.github.io/tags). 

## Authors

* **Ed Oswald Go** - *Initial work* - [GitHub](https://github.com/edoswaldgo)

See also the list of [contributors](https://github.com/thegoldloop/thegoldloop.github.io/contributors) who participated in this project.

## License

See the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* TBD
