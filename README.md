# ee5415_week_3_linear_layout

LinearLayout is a ViewGroup that displays child View elements in a linear direction, either
vertically or horizontally. You should be careful about over-using the LinearLayout. If you
begin nesting multiple Linear Layouts, you may want to consider using a ConstraintLayout
instead (see next section).
1. Start a new project named Linear Layout.
2. Follow the hello-world-style to fill in these values:
  • Choose your project : Empty Activity
  • Application name : Linear Layout
  • Package name : com.example.linearlayout
  • Language : Java
  • Minimum API level: API 21: Android 5.0 (Lollipop)
  • Click Finish
  • Default created Activity:
  • Activity Name: MainActivity
  • Layout Name: activity_main
3. Modify the layout XML in res/layout/activity_main.xml
Carefully inspect this XML. There is a root LinearLayout that defines its orientation to be
vertical—all child Views (of which it has two) will be stacked vertically. The first child is another
LinearLayout that uses a horizontal orientation and the second child is a LinearLayout that
uses a vertical orientation. Each of these nested LinearLayouts contains several TextView
elements, which are oriented with each other in the manner defined by their parent LinearLayout.
4. By default the onCreate() method in the MainActivity.java is pointing to the XML
layout file located at res/layout/activity_main.xml. The setContentView(int)
method loads the layout file for the Activity, specified by the resource ID —
R.layout.activity_main refers to the res/layout/activity_main.xml layout file.
