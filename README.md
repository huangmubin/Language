# Language

iOS language localization tool.


# How to use?

1. Take the `Language` folder input the project.
2. Change the `Language_input.swift` 's libray_input function. Add your language key_value.
3. Use the `Language.standard.update(language_type: String)` 's function to change the language type, or default is device system language.
4. Use the `func localized(_ key: String) -> String` function to get the localed text.
5. Use the `(value as String).language` to get the localed text.
6. Use the `(value as UIView).language()` to changed this view and it's subviews text.

    * UILabel's text
    * UITextField's placeholder
    * UIButton's title
    * UISegmentedControl's segment title
