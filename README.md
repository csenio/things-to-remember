# things-to-remember

### snippets
```
rfcp -> functional component with prop types
imr -> import react
redux -> import connect from redux
```

### setting up themeProvider from react storybook with storybook
```
import React from "react";
import { ThemeProvider } from 'styled-components';
import {addDecorator } from "@storybook/react";

addDecorator((story) => (
      <ThemeProvider theme={theme}>
          {story()}
      </ThemeProvider>
))
```
