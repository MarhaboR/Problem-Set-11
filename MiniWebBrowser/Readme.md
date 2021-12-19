Author: Marhabo Rakhmatshoeva
Investigate the capabilities of JavaFX’s WebView control and WebEngine class, then create a JavaFX app that provides basic web browsing capabilities.

Download the JavaFX SDK: https://gluonhq.com/products/javafx/

Add JavaFX library: File -> Project Structure -> Libraries -> add library path->C:\javafx-sdk-11.0.2\lib

Add VM Options: Run-> Edit Configuration -> modify options -> add vm options --module-path %PATH_TO_JAVAFX_SDK/LIB% --add-modules=javafx.swing,javafx.graphics,javafx.fxml,javafx.media,javafx.web --add-reads javafx.graphics=ALL-UNNAMED --add-opens javafx.controls/com.sun.javafx.charts=ALL-UNNAMED --add-opens javafx.graphics/com.sun.javafx.iio=ALL-UNNAMED --add-opens javafx.graphics/com.sun.javafx.iio.common=ALL-UNNAMED --add-opens javafx.graphics/com.sun.javafx.css=ALL-UNNAMED --add-opens javafx.base/com.sun.javafx.runtime=ALL-UNNAMED



![14](https://user-images.githubusercontent.com/91888254/146683839-56696891-a2b3-4760-850c-d1e76b4733f6.png)
![15](https://user-images.githubusercontent.com/91888254/146683843-c0448120-0d30-4766-b071-10b677cf5c68.png)


