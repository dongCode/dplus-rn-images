# @dplus/images

> React Native 浏览图片.


- 🔥Pinch zoom for both iOS and Android
- 🔥Double tap to zoom for both iOS and Android
- 🔥Supports swipe-to-close animation
- 🔥Custom header and footer components
- 🔥Uses VirtualizedList to optimize image loading and rendering


## Installation

```bash
yarn add @dplus/images
```

or

```bash
npm install --save @dplus/images
```

## Usage

```jsx
import Images from "@dplus/images";

const images = [
  "https://images.unsplash.com/photo-1571501679680-de32f1e7aad4",
  "https://images.unsplash.com/photo-1573273787173-0eb81a833b34",
  "https://images.unsplash.com/photo-1569569970363-df7b6160d111"
];

<ImageView
  data={images}
/>
```


## Props

| Prop name                | Description                                                                                         | Type                                                        | Required |
| ------------------------ | --------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | -------- |
| `data`                 | 需要渲染的图片                                                                          | string[]                                               | true     |
| `imageContainerStyle`           | ViewStyle    | (imageSrc: ImageSource, index: number) => string | false 



## Contributing



## License

[MIT](LICENSE)
