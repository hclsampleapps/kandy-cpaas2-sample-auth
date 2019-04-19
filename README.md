# kandy-cpaas2-sample-auth

### Auth app

This app will generate auth token for accessing further APIs.

 - Try the [demo](https://hclsampleapps.github.io/kandy-cpaas2-sample-auth/app/)
 - Get the [source code](https://github.com/hclsampleapps/kandy-cpaas2-sample-auth)

#### User manual 

1. Create an account on **AT&T** portal via [Register now for a free account](https://apimarket.att.com/signup).
2. Open an instance of `index.html` in the browser for a *User*.
3. Enter the *server URL*, for e.g.,
	- For AT&T API Marketplace [apimarket.att.com](https://apimarket.att.com), enter `https://oauth-cpaas.att.com`
4. Choose to get accessToken by *Password Grant* flow or *Client Credentials* flow.
5. Login using *User*'s credential in the browser window.
6. For **Password Grant** flow, enter 
	- *clientId* 
	- *emailId* 
	- *password*  
7. For **Client Credentials Grant** flow, enter
	- *privateKey*
	- *privateSecret*   
8. Click ***Login***
9. After successful login you will get an *accessToken* that you can use to explore the other APIs.

##### Notes

 - Existing user can confirm their account via [Log in to AT&T API Marketplace](https://apimarket.att.com/login)
 - You can download *kandy.js* from [Developer documentation - SDKs](https://apimarket.att.com/developer/sdks/javascript)

### Development

To setup the project repository, run these commands

```
git clone https://github.com/hclsampleapps/kandy-cpaas2-sample-auth.git
cd kandy-cpaas2-sample-auth
```

Then, open ```index.html``` in the browser to view the app.

#### Branching strategy

To learn about the branching strategy, contribution & coding conventions followed in the project, please refer [GitFlow based branching strategy for your project repository](https://gist.github.com/ribbon-abku/10d3fc1cff5c35a2df401196678e258a)
