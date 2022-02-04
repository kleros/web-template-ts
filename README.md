# WebTemplate

WebTemplate is a template to quickstart web development with no config. The stack used is:
- Yarn
- Parcel
- Typescript
- React
- StyledComponents
- ESlint
- Prettier
- Husky
- CommitLint

## Usage

The first thing you need is all the files in the directory, you can achieve this in a couple of ways:
- Fork this repo and ```git clone``` the fork.
- Download source code from releases (use this if your webpage is part of a bigger repo and not a repo by itself). Note that this option won't have husky, lintstaged nor commitlint.

If you want to use yarn berry, ```yarn set version berry``` and before doing anything else, make sure that the ```.yarnrc.yml``` has the line ```nodeLinker: node-modules```.

Then run ```yarn``` to install all dependencies. The scripts provided are:
- ```yarn start```: Start development server.
- ```yarn build```: Build your project for production.
- ```yarn clean```: Remove the previous build output.
- ```yarn clear```: Remove parcel cache.
- ```yarn check-style```: Runs eslint.
- ```yarn check-types```: Runs typescript compiler to check compliance.

## License
[MIT](https://choosealicense.com/licenses/mit/)
