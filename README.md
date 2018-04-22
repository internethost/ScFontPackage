# ScFontPackage 0.1.19
Font-Package mit freien Schriftarten zum Einbinden in JavaFx-Anwendungen inkl. css-File und Klasse mit den zu den jeweiligen FontAwesome-Icon-Namen zugehörigen Unicode.

BITTE BEACHTEN: Die Schriftarten unterliegen den jeweiligen Lizenzen der Autoren.

Enthält:
- FontAwesome (Font Awesome by Dave Gandy - http://fontawesome.io - SIL OPEN FONT LICENSE)
- Arimo (Apache 2.0 license)

## Nutzung: (MY-NODE durch den passenden Bezeichner ersetzen)

### Stylesheet auf Node setzen:
MY-NODE.getStylesheets().add(getClass().getResource("/de/sascha_schneider/res/fonts/fonts.css").toExternalForm());

MY-NODE.getStylesheets().add(getClass().getResource("my-node.css").toExternalForm());

MY-NODE.getStyleClass().add("my-node");

### Label mit FontAwesome-Icon erzeugen:
MY-NODE.add(new Label(FontAwesome.FA_QUESTION_CIRCLE_O));

### CSS-Datei my-node.css:
.my-node {
    -fx-font-family: 'FontAwesome';
}
