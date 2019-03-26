# things-to-remember

## setting up themeProvder from react storybook with storybook
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
