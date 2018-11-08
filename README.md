# UCSB Bootstrap Theme

Implementation of the [UCSB Visual Identity](https://www.ucsb.edu/visual-identity)
as a Bootstrap theme.

## Approach

The overall goal of this project is to create a Bootstrap theme of the
[UCSB Visual Identity](https://www.ucsb.edu/visual-identity) guidelines with as
little custom CSS as possible. In other words, this project will attempt to
emulate the UCSB Visual Identity by primarily using built-in Bootstrap components
and by setting Bootstrap theming variables. Of course, in cases where more
styling is necessary, custom CSS will be used.

This approach is to ensure that those using this theme can rely on the fact that
Bootstrap will behave as it normally behaves, allowing those familiar with
Bootstrap to easily apply their knowledge when working with this template.

## Contributing

To suggest an update for this project or identify a bug, please
create a [new issue](https://github.com/UCSantaBarbara/ucsb-bootstrap/issues/new).

If you would like to submit your own updates to this project, please follow
these steps:

1. If an issue doesn't exist describing the change, [create a new issue](https://github.com/UCSantaBarbara/ucsb-bootstrap/issues/new)
2. [Create your own fork](https://help.github.com/articles/fork-a-repo/) of this repository
3. [Create a local clone](https://help.github.com/articles/cloning-a-repository/) of your fork
4. [Create a new branch](https://guides.github.com/introduction/flow/) on your clone to contain your changes
5. Make your changes (see "Developing Locally" below)
6. Push your changes to your fork
7. Create a [pull request](https://help.github.com/articles/about-pull-requests/) with your changes, referencing the issue in your pull request

A contributor with the ability to accept pull requests for this repository will
review your changes and accept the pull request or suggest further updates.

## Developing Locally

To get the theme running locally on your computer, run the following commands:

1. `git clone https://github.com/UCSantaBarbara/ucsb-bootstrap` (ideally, you would [clone your own fork](https://help.github.com/articles/fork-a-repo/))
2. `cd ucsb-bootstrap`
3. `npm install`
4. `npm run scss`

Now, when you make any changes to the `.scss` files in the `./scss` directory,
they will be automatically compiled into the `./css/ucsb.css` file.

You can view the impact of these changes by opening up the `index.html` file
in the `./docs` directory.
