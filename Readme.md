# Publishing a package to npm

Publishing a package to npm is really straight forward and easy.
Follow the below steps to publish an npm package.

### Step 1

## **Sigup to npm**

Create an npm account by using the below link

[NPM Signup](https://www.npmjs.com/signup)

Follow the procedure and create an account

---

### Step 2

## **Npm login**

Open the terminal in project level and run the following command.

```
npm login
```

provide the respective details and it will send a one-time password to registered email for verification.

---
 
### Step 3

## **Creating a package.json**

Run the following command

```
npm init
```

This will generate a package.json provide a unique package name and respective details and other fields are optional


---

### Step 4

## Publishing the package

Run the following command to publish your package

```
npm publish
```

If everything goes well it will show your package name with version.

Test you package by running the following command.

```
npm install <your package name>
```
---