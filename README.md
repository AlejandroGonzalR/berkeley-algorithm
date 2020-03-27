# Implementation of Berkeley Algorithm

Berkeley’s Algorithm is a clock synchronization technique used in distributed systems. The algorithm assumes that each machine node in the network either doesn’t have an accurate time source or doesn’t possess an UTC server.

## Getting Started

It's pretty simple, install the project dependencies with **npm** and run the start script:

```
npm start
```

The app will be available on port [5000](http://localhost:5000/). You can instantiate the application multiple times and configure the time in each of them, so that the time in each instance is updated automatically every minute.

![editor screenshot](https://github.com/AlejandroGonzalR/berkeley-algorithm/blob/master/public/images/BerkeleyScreenshot.png)

## Built With

* [Node.js 12.16.1 LTS](https://maven.apache.org/) - Runtime environment
* See also the used [packages](https://github.com/AlejandroGonzalR/berkeley-algorithm/blob/master/package.json)

## Authors

* **Alejandro González Rodríguez** - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
