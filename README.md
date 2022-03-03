
# Clorastore ~ Firestore as local database

 This is a local implementation of cloud firestore for android. Clorastore stores data in form of documents as [firestore](https://firebase.google.com/) and [mongoDB](https://www.mongodb.com/) does.
 The main aim of making this database is to make developer life easier. Programmer does not need to know that stupid SQL queries for just simple CRUD operations.
 This is the second easiest database ever made for android after [CloremDB](https://github.com/ErrorxCode/CloremDB).
 Although, this is similar to those of **Firestore** and **Mongo DB** but also differ in some ways. In Clorastore, collections can a contain collection whereas document can't.
 Each document is limited to 10 MB.

![image](/data-storage.png)

## Features

- Easy,lightweight and fast
- Capable of storing almost all datatype
- Use document and collections to store data
- High level querying engine

  
## Acknowledgements
 - [Document oriented database](https://en.wikipedia.org/wiki/Document-oriented_database)
	
## Documentation
- [Javadocs](https://errorxcode.github.io/docs/clorastore/index.html)
- [Guide](https://github.com/ErrorxCode/ClorastoreDB/wiki/Documentation)

  
## Deployment / Installation
 In your project build.gradle
```groovy
 allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
In your app build.gradle
```groovy
dependencies {
	        implementation 'com.github.ErrorxCode:ClorastoreDB:2.0'
	}
```

## It's easy
```java
Clorastore.insert().and().read().finish();
```

## Contribution
Contribution are always welcome. Rules and `code of conduct` are same. Please make a issue or pull request regarding any feature or bug.

### Sponsored by ❤
#### [Clorabase](https://clorabase.netlify.app)
> A account-less platform as a service for android apps. (PaaS)
