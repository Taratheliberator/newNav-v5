1. После скачивания оригинальной версии сначала вышла ошибка, она разобрана в https://www.youtube.com/watch?v=xVyLa-EAoCk
2. Потом ошибка TypeError: undefined is not an object (evaluating '\_reactNativePaper.DarkTheme.colors')
   в названиях световой темы в библиотеке react-native-paper. В App.js вместо DarkTheme, DefaultTheme надо написать MD3DarkTheme, MD3LightTheme
