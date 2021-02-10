<div align="center">
	<br>
	<br>
	<h1>rlayouts</h1>
	<p>
		<b>Simple Layout Components for React</b>
	</p>
	<br>
	<br>
	<br>
</div>

# Motivation

I copy paste the same set of components for layout in almost every react project that I work on so this is going to act as a base from now. I still prefer copying the original code around to make it easier to modify and fix when needed.

You can find the web code snippets here [reaper.im/collections](https://reaper.im/collections/code)

# Installation

```sh
npm i @barelyreaper/rlayouts
#or
yarn add @barelyreaper/rlayouts
```

# Usage

I'm still writing proper docs, you can use the below type defs to understand the gist.

```ts
declare type IPadding = {
  children: React.ReactNode;
  x: number;
  y: number;
  all: number;
};

declare type ISpacer = {
  inline: boolean;
  x: number;
  y: number;
};
```

# Roadmap

- [x] Padding
- [x] Spacer
- [ ] Row
- [ ] Col
- [ ] Card

# Dev

- Make sure you have `yarn` installed and node version greater than `12`,
- Run the below commands in the order for starting the dev server

## For Contributors

- Make sure you fork the repository and are using the `main` branch for the latest code
- Make sure your git commit messages follow the `commitlint` standard as [commitlog](https://github.com/barelyhuman/commitlog) will be used to generate changelogs.
- We prefer rebasing the commit over Merge, so create a feature branch, create your list of commits, squash them into a single commit so we can rebase a single feature commit.

```sh
yarn
yarn dev
```

# Build

```sh
yarn build
```
