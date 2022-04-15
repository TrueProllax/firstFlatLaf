# firstFlatLaf

Example uses library FlatLaf

How uses library?

1) The first way

1. add lirbray in project (link - https://search.maven.org/artifact/com.formdev/flatlaf/2.1/jar)

![image](https://user-images.githubusercontent.com/92289766/163592466-b5c65a6d-1903-4ffe-a6e4-7e114b0f1f25.png)

3. go to the code project (main class JFrame your project)
4. for us need foollowing code from method

![image](https://user-images.githubusercontent.com/92289766/163592043-86259fd9-0604-42dc-ab31-64cdc54a7e43.png)

4. delete code and write try / catch


![image](https://user-images.githubusercontent.com/92289766/163592193-2e0529d8-1fd9-4e71-973a-6f38604eae65.png)

5. write following code

UIManager.setLookAndFeel(new FlatIntelliJLaf());

![image](https://user-images.githubusercontent.com/92289766/163592372-023482e3-d624-4dec-a461-c12422343134.png)

in project

![image](https://user-images.githubusercontent.com/92289766/163592521-3d8c55d7-9ca9-4118-adaa-b408079b6524.png)

2) The second way 

1. add library in project (link - https://www.formdev.com/flatlaf/themes/ , https://search.maven.org/artifact/com.formdev/flatlaf-intellij-themes/2.1/jar)

![image](https://user-images.githubusercontent.com/92289766/163592697-302871f3-80a9-4ffb-b609-16d84592abb5.png)

2. edit code

FlatCyanLightIJTheme.setup();

code

![image](https://user-images.githubusercontent.com/92289766/163592864-108cd40e-c8eb-45c1-9f58-aa856c63113d.png)

in project

![image](https://user-images.githubusercontent.com/92289766/163592902-956e1baf-5d49-4f70-9605-121ce93bed4e.png)

FlatSolarizedDarkContrastIJTheme.setup();

code 

![image](https://user-images.githubusercontent.com/92289766/163592964-c6742f7b-4549-4ac9-bdd0-2feb0a6233ea.png)

in project

![image](https://user-images.githubusercontent.com/92289766/163593017-46e447a1-f4b5-4725-aef5-6903c87efc1a.png)


End. Thank for attention!





