<!-- markdownlint-disable MD030 -->

# OSMI AI Embed React

React library to display OSMI AI chatbot on your website

![OSMI AI](https://github.com/artstyleplaystyle/OSMIChatEmbed/blob/main/images/ChatEmbed.gif?raw=true)

## Install

```bash
npm install osmi-ai-embed osmi-ai-embed-react
```

or

```bash
yarn add osmi-ai-embed osmi-ai-embed-react
```

## Import

Full Page Chat

```tsx
import { FullPageChat } from "osmi-ai-embed-react";

const App = () => {
  return (
    <FullPageChat
      chatflowid="your-chatflow-id"
      apiHost="http://localhost:3000"
    />
  );
};
```

Popup Chat

```tsx
import { BubbleChat } from "osmi-ai-embed-react";

const App = () => {
  return (
    <BubbleChat chatflowid="your-chatflow-id" apiHost="http://localhost:3000" />
  );
};
```
