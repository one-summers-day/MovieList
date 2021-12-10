
# Movie List

## Getting Started

1. Fork and clone this repo, then open two terminal tabs and navigate to the root directory.

2. In one of the two seperate terminal tabs run the following script:
  ```
  npm start
  ```

3. In the second terminal tab run:
  ```
  npm run react-dev
  ```

4. Open localhost:3000 in the browser and you should see **Hello World!** if React is running correctly.

Now you can get started building the application by visiting gLearn and following the next instructions there.

# Logos

## High Level Approach

### Level 0

- [ ] A movieListElement should correspond to a react component. The movieList, therefore, is a react component of react components.

- [ ] Iterate through ```movies``` and hardcode them.

### Level 1

- [ ] Make a searchbar using some HTML inside a react component.

- [ ] Add an eventListener (make the button stateful) so when it is triggered, only those react elements with matching names are displayed.

  - [ ] Add an extra clause to 2 to catch cases where there are no such react elements with the given movie name


### Level 2

- [ ] Make an input field using some HTML elements inside a react component.

- [ ] Make the ADD button push user entries into an array, which is dynamically rendered using an iterator inside the ```App.render()``` method

### Level 3

- [ ] Modify the movieList element made in Level 0 such that it now contains a button toggle on the far right.

- [ ] **Refactor movieListElement into a stateful component.**

- [ ] Filter based on movieListElement state to display the appropriate list.

### Level 4 / Level 5

- This seems like overkill with the amount of time available, so skipping it for now

## System Architecture

- Refer to [this diagram made with Excalidraw](https://www.google.org)