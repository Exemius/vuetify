---
meta:
  title: Button component
  description: The button component communicates actions that a user can take and are typically placed in dialogs, forms, cards and toolbars.
  keywords: buttons, vuetify button component, vue button component
related:
  - /components/button-groups/
  - /components/icons/
  - /components/floating-action-buttons/
---

# Buttons

The `v-btn` component replaces the standard html button with a material design theme and a multitude of options. Any color helper class can be used to alter the background or text color. <inline-ad slug="scrimba-buttons" />

<entry-ad />

## Usage

Buttons in their simplest form contain uppercase text, a slight elevation, hover effect, and a ripple effect on click.

<usage name="v-btn" />

## API

- [v-btn](/api/v-btn)
- [v-btn-toggle](/api/v-btn-toggle)

<inline-api page="components/buttons" />

## Caveats

<alert type="warning">

  `v-btn` is the only component that behaves differently when using the **dark** prop. Normally components use the **dark** prop to denote that they have a dark colored background and need their text to be white. While this will work for `v-btn`, it is advised to only use the prop when the button **IS ON** a colored background due to the disabled state blending in with white backgrounds. If you need white text, simply add the `white--text` class.

</alert>

## Examples

### Props

#### Block

**block** buttons extend the full available width.

<example file="v-btn/prop-block" />

#### Depressed

**depressed** buttons still maintain their background color, but have no box shadow.

<example file="v-btn/prop-depressed" />

#### Floating

Floating buttons are rounded and usually contain an icon.

<example file="v-btn/prop-floating" />

#### Icon

Icons can be used for the primary content of a button. This property makes the button rounded and applies the **text** prop styles.

<example file="v-btn/prop-icon" />

#### Loaders

Using the loading prop, you can notify a user that there is processing taking place. The default behavior is to use a `v-progress-circular` component but this can be customized.

<example file="v-btn/prop-loaders" />

<random-ad />

#### Outlined

**outlined** buttons inherit their borders from the current color applied.

<example file="v-btn/prop-outlined" />

#### Plain

**plain** buttons have a lower baseline opacity that reacts to **hover** and **focus**.

<example file="v-btn/prop-plain" />

#### Rounded

**rounded** buttons behave the same as regular buttons but have rounded edges.

<example file="v-btn/prop-rounded" />

#### Sizing

Buttons can be given different sizing options to fit a multitude of scenarios.

<example file="v-btn/prop-sizing" />

#### Text

Text buttons have no box shadow and no background. Only on hover is the container for the button shown. When used with the **color** prop, the supplied color is applied to the button text instead of the background.

<example file="v-btn/prop-text" />

#### Tile

**tile** buttons behave the same as regular buttons but have no border radius.

<example file="v-btn/prop-tile" />

### Misc

#### Raised

**raised** buttons have a box shadow that increases when clicked. This is the default style.

<example file="v-btn/misc-raised" />

<backmatter />
