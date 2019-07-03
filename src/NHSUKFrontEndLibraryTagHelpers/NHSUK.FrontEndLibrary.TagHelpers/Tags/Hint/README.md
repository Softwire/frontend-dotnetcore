﻿# Hint

To discuss or contribute to this component, visit the [GitHub issue for this component]().

## Guidance

Find out more about the hint component and when to use it in the [NHS digital service manual](https://beta.nhs.uk/service-manual/styles-components-patterns/hint-text).

## Quick start example

[Preview the hint component]()

### HTML markup

```html
<span class="nhsuk-hint">
  It’s on your National Insurance card, benefit letter, payslip or P60. For example, ‘QQ 12 34 56 C’.
</span>
```

### Taghelper

```
<nhs-hint nhs-hint-type="Standard">It’s on your National Insurance card, benefit letter, payslip or P60. For example, ‘QQ 12 34 56 C’.</nhs-hint>
```

### Taghelper

The hint taghelper takes the following attributes:

| Name                    | Type     | Required  | Description             |
| ------------------------|----------|-----------|-------------------------|
| **nhs-hint-type**                | string   | Yes       | specifies the type of hint e.g Standard, checkboxes, radio.  |
| **classes**             | string   | No        | Optional additional classes to add to the breadcrumbs container. Separate each class with a space. |
| **id**                  | string   | No       | Optional id attribute to add to the hint span tag. |

This component and documentation has been taken from [NHS.UK Frontend - Hint component](https://github.com/nhsuk/nhsuk-frontend/tree/master/packages/components/hint) with a few minor adaptations.