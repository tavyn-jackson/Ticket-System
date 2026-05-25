## Defects Encountered

### TemplateNotFound Error

Issue:
Template file could not be located.

Cause:
Incorrect file name.

Resolution:
Renamed template to match render_template() reference.

---

### Module Import Error

Issue:
No module named app.

Cause:
Pytest could not locate application module.

Resolution:
Adjusted Python path configuration.

---

### Duplicate Route Error

Issue:
View function mapping overwriting existing endpoint.

Cause:
Duplicate login routes.

Resolution:
Removed duplicate route definition.
