# Parametrized Issue Template for github

A test project to demonstrate how to create a parametrized issue template (bug report) for a project on GitHub.

# Populating fields automagically

This can be used to automatically populate fields when user clicks `report a bug` in your application.

For example you can populate the bug with known information by invoking this in the terminal:
`open "https://github.com/pskowronek/parametrized_issue_template/issues/new?labels=bug&template=bug_report.yml&title=[Bug]%3A+&version=1.2.3&java-version=18&os-version=macOS%0A1.2.3&logs=some%0Alogs%0Aare%20here"`

This way a program can pre-fill fields (like versions, os type, logs) programatically if somebody wants to report a bug.
