# isomorphic-boilerplate
Opinionated Isomorphic Boilerplate. Most of the structure is common regardless of your isomorphic stack.
I'm using Node.js + React.js + Webpack + Redux


# File Structure
File structure is the most important aspect in building a well defined architecture. Below is t
```
.
app/
├── routes/
├── components/              // React components
├── libs/                    // Custom modules
├── controllers/
├── store/
├── styles/                  // SCSS/LESS styles
├── client.js
├── server.js
build/
config/
├── default.json
├── production.json
├── development.json
├── index.js                  // Return merged final config based on environment
node_modules/
public/
├── images/
package.json
webpack.config.js
```
