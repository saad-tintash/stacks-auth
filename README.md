## Stacks wallet connect

*[This is by no means a guide. Just the steps I followed while learning react, typescript, stacks eco and clarity. Will extend / fork & create an FT app around it, using Clarity smart contract]*

simple app using @stacks/connect-react & @stacks/ui to connect stacks wallet. 

App borrows a lot from [Heystack](https://docs.stacks.co/build-apps/examples/heystack#heystack-overview) on [staks](https://stacks.org)

1. create and verify template 
```
npx create-react-app stacks-auth --template typescript  
yarn start 
```
2. cleanup template *[first commit in this repo]*
3. add sample auth code from [link](https://docs.stacks.co/build-apps/guides/authentication#usage-in-react-apps)
4. add dependencies, specially
   - @stacks/ui 
   - @stacks/connect-react
5. Note above code won't work straight away, wrap it in a function first
6. At this point app should connect with wallet account 

#### User session & state management 
1. add required hooks and componenets from [Heystack]()
2. Install state management lib - Jotai
3. add logout button in user-area 