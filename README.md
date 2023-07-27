Because we are using styled-components of MUI and the project is built with yarn so make sure your package.json dependencies are installed with the following dependencies:
"@mui/styled-engine": "npm:@mui/styled-engine-sc@latest",

Add a resolution to the project in the package.json file:
  "resolutions": {
    "@mui/styled-engine": "npm:@mui/styled-engine-sc@latest"
  },

For more details of the Material UI installation, see https://mui.com/material-ui/getting-started/installation/ and https://mui.com/material-ui/guides/styled-engine/

Make sure your local host port is set to the specified port according to the configuration of backend configuration.