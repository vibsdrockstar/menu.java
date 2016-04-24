# menu.java
this would show you how we create menus in java or javafx
import java.application.Application;
import java.scene.Scene;
import java.scene.control.*;
import java.scene.layout.BorderPane;
import java.stage.Stage;
public class Main extends Application{
Stage window;
Border Pane layout:
public static void main(String[] args){
launch(args);

}
@Override
public void start(Stage primarystage ) throws Exception{
window=primaryStage;
window.setTitle("WeatherForecast");
// 3 days
Menu 3dayMenu=new Menu("3 Days");
//7 days
Menu 7dayMenu=new Menu("7 days");
//10 days
Menu 10dayMenu=new Menu("10 days");
layout=new BorderPane();
Scene.scene=new Scene(layout,400,300);
window.setScene(scene);
window.show();
}
}
