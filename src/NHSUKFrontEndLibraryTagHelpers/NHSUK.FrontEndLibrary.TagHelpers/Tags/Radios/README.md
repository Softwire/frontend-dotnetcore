﻿# Radios

To discuss or contribute to this component, visit the [GitHub issue for this component]().

## Guidance

Find out more about the radios component and when to use it in the [NHS digital service manual](https://beta.nhs.uk/service-manual/styles-components-patterns/radios).

## Quick start examples

### Radios

[Preview the radios component]()

#### HTML markup

```html
<div class="nhsuk-form-group">
  <fieldset class="nhsuk-fieldset" aria-describedby="example-hint">
    <legend class="nhsuk-fieldset__legend">
      Have you changed your name?
    </legend>
    <span class="nhsuk-hint" id="example-hint">
    This includes changing your last name or spelling your name differently.
    </span>
    <div class="nhsuk-radios">
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-1" name="example" type="radio" value="yes">
        <label class="nhsuk-label nhsuk-radios__label" for="example-1">
        Yes
        </label>
      </div>
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-2" name="example" type="radio" value="no" checked>
        <label class="nhsuk-label nhsuk-radios__label" for="example-2">
        No
        </label>
      </div>
    </div>
  </fieldset>
</div>
```

#### Taghelper

```
<nhs-form-group nhs-form-group-type="Standard">
  <nhs-fieldset aria-describedby="example-hint">
    <nhs-fieldset-legend nhs-legend-size="Standard">Have you changed your name?</nhs-fieldset-legend>
    <nhs-hint nhs-hint-type="Standard" id="example-hint">This includes changing your last name or spelling your name differently.</nhs-hint>
    <nhs-radios nhs-radios-type="Standard">
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-1" name="example" value="yes"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-1">Yes</nhs-label>
      </nhs-radios-item>
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-2" name="example" value="no" checked></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-2">No</nhs-label>
      </nhs-radios-item>
    </nhs-radios>
  </nhs-fieldset>
</nhs-form-group>

```
---

### Radios inline

[Preview the radios inline component]()

#### HTML markup

```html
<div class="nhsuk-form-group">
  <fieldset class="nhsuk-fieldset" aria-describedby="example-hint">
    <legend class="nhsuk-fieldset__legend">
      Have you changed your name?
    </legend>
    <span class="nhsuk-hint" id="example-hint">
    This includes changing your last name or spelling your name differently.
    </span>
    <div class="nhsuk-radios nhsuk-radios--inline">
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-1" name="example" type="radio" value="yes">
        <label class="nhsuk-label nhsuk-radios__label" for="example-1">
        Yes
        </label>
      </div>
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-2" name="example" type="radio" value="no" checked>
        <label class="nhsuk-label nhsuk-radios__label" for="example-2">
        No
        </label>
      </div>
    </div>
  </fieldset>
</div>
```

#### Taghelper

```
<nhs-form-group nhs-form-group-type="Standard">
  <nhs-fieldset aria-describedby="example-hint">
    <nhs-fieldset-legend nhs-legend-size="Standard">Have you changed your name?</nhs-fieldset-legend>
    <nhs-hint nhs-hint-type="Standard" id="example-hint">This includes changing your last name or spelling your name differently.</nhs-hint>
    <nhs-radios nhs-radios-type="Inline">
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-1" name="example" value="yes"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-1">Yes</nhs-label>
      </nhs-radios-item>
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-2" name="example" value="no" checked></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-2">No</nhs-label>
      </nhs-radios-item>
    </nhs-radios>
  </nhs-fieldset>
</nhs-form-group>

```
---

### Radios disabled

[Preview the radios disabled component]()

#### HTML markup

```html
<div class="nhsuk-form-group">
  <fieldset class="nhsuk-fieldset" aria-describedby="example-disabled-hint">
    <legend class="nhsuk-fieldset__legend">
      Have you changed your name?
    </legend>
    <span class="nhsuk-hint" id="example-disabled-hint">
    This includes changing your last name or spelling your name differently.
    </span>
    <div class="nhsuk-radios">
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-disabled-1" name="example-disabled" type="radio" value="yes" disabled>
        <label class="nhsuk-label nhsuk-radios__label" for="example-disabled-1">
        Yes
        </label>
      </div>
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-disabled-2" name="example-disabled" type="radio" value="no" disabled>
        <label class="nhsuk-label nhsuk-radios__label" for="example-disabled-2">
        No
        </label>
      </div>
    </div>
  </fieldset>
</div>
```

#### Taghelper

```
<nhs-form-group nhs-form-group-type="Standard">
  <nhs-fieldset aria-describedby="example-disabled-hint">
    <nhs-fieldset-legend nhs-legend-size="Standard">Have you changed your name?</nhs-fieldset-legend>
    <nhs-hint nhs-hint-type="Standard" id="example-hint">This includes changing your last name or spelling your name differently.</nhs-hint>
    <nhs-radios nhs-radios-type="Standard">
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-disabled-1" name="example-disabled" value="yes" disabled></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-disabled-1">Yes</nhs-label>
      </nhs-radios-item>
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-disabled-2" name="example-disabled" value="no" disabled></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-disabled-2">No</nhs-label>
      </nhs-radios-item>
    </nhs-radios>
  </nhs-fieldset>
</nhs-form-group>

```
---

### Radios with a divider

[Preview the radios with a divider component]()

#### HTML markup

```html
<div class="nhsuk-form-group">
  <fieldset class="nhsuk-fieldset">
    <legend class="nhsuk-fieldset__legend">
      How do you want to sign in?
    </legend>
    <div class="nhsuk-radios">
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-divider-1" name="example" type="radio" value="government-gateway">
        <label class="nhsuk-label nhsuk-radios__label" for="example-divider-1">
        Use Government Gateway
        </label>
      </div>
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-divider-2" name="example" type="radio" value="nhsuk-login">
        <label class="nhsuk-label nhsuk-radios__label" for="example-divider-2">
        Use NHS.UK login
        </label>
      </div>
      <div class="nhsuk-radios__divider">or</div>
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-divider-4" name="example" type="radio" value="create-account">
        <label class="nhsuk-label nhsuk-radios__label" for="example-divider-4">
        Create an account
        </label>
      </div>
    </div>
  </fieldset>
</div>
```

#### Taghelper

```
<nhs-form-group nhs-form-group-type="Standard">
  <nhs-fieldset>
    <nhs-fieldset-legend nhs-legend-size="Standard"> How do you want to sign in?</nhs-fieldset-legend>
    <nhs-radios nhs-radios-type="Standard">
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-divider-1" name="example" value="government-gateway"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-divider-1">Use Government Gateway</nhs-label>
      </nhs-radios-item>
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-divider-2" name="example" value="nhsuk-login"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-divider-2">Use NHS.UK login</nhs-label>
      </nhs-radios-item>
      <nhs-radios-divider>or</nhs-radios-divider>
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-divider-4" name="example" value="create-account"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-divider-4">Create an account</nhs-label>
      </nhs-radios-item>
    </nhs-radios>
  </nhs-fieldset>
</nhs-form-group>

```
---

### Radios with hint text on items

[Preview the radios with hint text on items component]()

#### HTML markup

```html
<div class="nhsuk-form-group">
  <fieldset class="nhsuk-fieldset">
    <legend class="nhsuk-fieldset__legend">
      <h1 class="nhsuk-fieldset__heading">
        How do you want to sign in?
      </h1>
    </legend>
    <div class="nhsuk-radios">
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="gov-1" name="gov" type="radio" value="gateway" aria-describedby="gov-1-item-hint">
        <label class="nhsuk-label nhsuk-radios__label" for="gov-1">
        Sign in with Government Gateway
        </label>
        <span class="nhsuk-hint nhsuk-radios__hint" id="gov-1-item-hint">
        You&#39;ll have a user ID if you've registered for self-assessment or filed a tax return online before.
        </span>
      </div>
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="gov-2" name="gov" type="radio" value="verify" aria-describedby="gov-2-item-hint">
        <label class="nhsuk-label nhsuk-radios__label" for="gov-2">
        Sign in with NHS.UK login
        </label>
        <span class="nhsuk-hint nhsuk-radios__hint" id="gov-2-item-hint">
        You’ll have an account if you’ve already proved your identity with either Barclays, CitizenSafe, Digidentity, Experian, Post Office, Royal Mail or SecureIdentity.
        </span>
      </div>
    </div>
  </fieldset>
</div>
```

#### Taghelper

```
<nhs-form-group nhs-form-group-type="Standard">
  <nhs-fieldset>
    <nhs-fieldset-legend nhs-legend-size="Standard" is-page-heading="true">
      How do you want to sign in?
    </nhs-fieldset-legend>
    <nhs-radios nhs-radios-type="Standard">
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="gov-1" name="gov" value="gateway" aria-describedby="gov-1-item-hint"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="gov-1">Sign in with Government Gateway</nhs-label>
        <nhs-hint nhs-hint-type="Radios" id="gov-1-item-hint">
          You'll have a user ID if you've registered for self-assessment or filed a tax return online before.
        </nhs-hint>
      </nhs-radios-item>
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="gov-2" name="gov" value="verify" aria-describedby="gov-2-item-hint"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="gov-2">Sign in with NHS.UK login</nhs-label>
        <nhs-hint nhs-hint-type="Radios" id="gov-2-item-hint">
          You’ll have an account if you’ve already proved your identity with either Barclays, CitizenSafe, Digidentity, Experian, Post Office, Royal Mail or SecureIdentity.
        </nhs-hint>
      </nhs-radios-item>
    </nhs-radios>
  </nhs-fieldset>
</nhs-form-group>

```
---

### Radios without fieldset

[Preview the radios without fieldset component]()

#### HTML markup

```html
<div class="nhsuk-form-group">
  <div class="nhsuk-radios">
    <div class="nhsuk-radios__item">
      <input class="nhsuk-radios__input" id="colours-1" name="colours" type="radio" value="red">
      <label class="nhsuk-label nhsuk-radios__label" for="colours-1">
      Red
      </label>
    </div>
    <div class="nhsuk-radios__item">
      <input class="nhsuk-radios__input" id="colours-2" name="colours" type="radio" value="green">
      <label class="nhsuk-label nhsuk-radios__label" for="colours-2">
      Green
      </label>
    </div>
    <div class="nhsuk-radios__item">
      <input class="nhsuk-radios__input" id="colours-3" name="colours" type="radio" value="blue">
      <label class="nhsuk-label nhsuk-radios__label" for="colours-3">
      Blue
      </label>
    </div>
  </div>
</div>
```

#### Taghelper

```
<nhs-form-group nhs-form-group-type="Standard">
  <nhs-radios nhs-radios-type="Standard">
    <nhs-radios-item>
      <nhs-input nhs-input-type="Radios" id="colours-1" name="colours" value="red"></nhs-input>
      <nhs-label nhs-label-type="Radios" for="colours-1">Red</nhs-label>
    </nhs-radios-item>
    <nhs-radios-item>
      <nhs-input nhs-input-type="Radios" id="colours-2" name="colours" value="green"></nhs-input>
      <nhs-label nhs-label-type="Radios" for="colours-2">Green</nhs-label>
    </nhs-radios-item>
    <nhs-radios-item>
      <nhs-input nhs-input-type="Radios" id="colours-3" name="colours" value="blue"></nhs-input>
      <nhs-label nhs-label-type="Radios" for="colours-3">Blue</nhs-label>
    </nhs-radios-item>
  </nhs-radios>
</nhs-form-group>
```
---

### Radios with hint text and error message

[Preview the radios with hint text and error message component]()

#### HTML markup

```html
<div class="nhsuk-form-group nhsuk-form-group--error">
  <fieldset class="nhsuk-fieldset app-fieldset--custom-modifier" aria-describedby="example-hint example-error" data-attribute="value" data-second-attribute="second-value">
    <legend class="nhsuk-fieldset__legend">
      Have you changed your name?
    </legend>
    <span class="nhsuk-hint" id="example-hint">
    This includes changing your last name or spelling your name differently.
    </span>
    <span id="example-error" class="nhsuk-error-message">
    Please select an option
    </span>
    <div class="nhsuk-radios">
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-1" name="example" type="radio" value="yes">
        <label class="nhsuk-label nhsuk-radios__label" for="example-1">
        Yes
        </label>
      </div>
      <div class="nhsuk-radios__item">
        <input class="nhsuk-radios__input" id="example-2" name="example" type="radio" value="no" checked>
        <label class="nhsuk-label nhsuk-radios__label" for="example-2">
        No
        </label>
      </div>
    </div>
  </fieldset>
</div>
```

#### Taghelper

```
<nhs-form-group nhs-form-group-type="Error">
  <nhs-fieldset aria-describedby="example-hint example-error" data-attribute="value" data-second-attribute="second-value">
    <nhs-fieldset-legend nhs-legend-size="Standard">Have you changed your name?</nhs-fieldset-legend>
    <nhs-hint nhs-hint-type="Standard" id="example-hint">This includes changing your last name or spelling your name differently.</nhs-hint>
    <nhs-error-message id="example-error">Please select an option</nhs-error-message>
    <nhs-radios nhs-radios-type="Standard">
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-1" name="example" value="yes"></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-1">Yes</nhs-label>
      </nhs-radios-item>
      <nhs-radios-item>
        <nhs-input nhs-input-type="Radios" id="example-2" name="example" value="no" checked></nhs-input>
        <nhs-label nhs-label-type="Radios" for="example-2">No</nhs-label>
      </nhs-radios-item>
    </nhs-radios>
  </nhs-fieldset>
</nhs-form-group>

```
---
### Taghelper

| Name                | Type     | Required  | Description                 |
| --------------------|----------|-----------|-----------------------------|
| **nhs-form-group**           | Taghelper   | Yes        | The formgroup taghelper wrapper for the radios component.|
| **nhs-fieldset**        | Taghelper   | No        | The fieldset taghelper. |
| **nhs-hint**            | Taghelper   | No        | The hint taghelper. |
| **nhs-radios-item**                | Taghelper   | Yes       | Taghelper representing a radios item.|
| **nhs-radios-type**                | string   | Yes       | radios type e.g Standard or Inline.|
| **nhs-radios-divider**                | Taghelper   | Yes       | Optional divider taghelper to separate radio items, for example the text "or"..|
| **nhs-errorMessage**    | Taghelper   | No        | The error message taghelper.|
| **classes**         | string   | No        | Optional additional classes to add to the radios container. Separate each class with a space. |


This component and documentation has been taken from [NHS.UK Frontend - Radios component](https://github.com/nhsuk/nhsuk-frontend/tree/master/packages/components/radios) with a few minor adaptations.