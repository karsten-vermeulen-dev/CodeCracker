## Create a game state system

<b>1.</b> Create a <i>MenuState</i> base class and derive some menu state child classes, such as <i>HelpState</i>, <i>TutorialState</i>, and <i>OptionsState</i>. <br>
<b>2.</b> Add properties and member functions to the base class and make sure to virtually override the <i>Update()</i> function. <br>
<b>3.</b> Each child's <i>Update()</i> function should display different text, i.e. help text for the <i>Helpstate</i>, a set of options for the <i>Optionstate</i>, etc. <br>
<b>4.</b> Create a menu with options for the user to select and whatever option they choose, create the corresponding menu state in memory and add that to a vector. <br>
<b>5.</b> Make sure to always call the <i>Update()</i> function of the state in the back of the vector. If the user exits the state, remove that state object from the vector. <br>
