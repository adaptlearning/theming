# Briefing Theme 2

## Files:

### Theme Specification (Theme_2-0_v2.docx)
This File should be somewhere in the @Theme chat
Describes the Concept and Rules of the new Theme.
Please see Section “Colour Variable usage” for what color-groups are allowed to use in which files.

### Google Spreadsheet
Lists [all the Variables](https://docs.google.com/spreadsheets/d/1l_heeNCofdAEqEA9AAkqjH5UOjo4UiEnIb27CuYLXH0) that are allowed for the new Theme.

### AD-Images
[Images](https://github.com/adaptlearning/theming)

### Base Framework (P101)
[Course](https://github.com/adaptlearning/theming/tree/master/framework_package) with all contrib Plugins. All components are displayed in all 3 Layouts (full, left, right).

### Theme Repository
[Repo](https://github.com/lc-thomasberger/adapt-theme-basic)

## Tasks

### Add Variable Files and remove duplicate Variable names:
- Colors.less (done)
- Paddings.less (done)
- Fonts.less (done)
- Generic.less (done)

### Update Styling based on AD:
- Navigation Bar (adapt_basic_menu.jpg)
  - PLP indicator
  - Change so that height is set by padding
- Blocks to full width (adapt_basic_assessment.jpg)
  - Be able to set bg-color with a css class from JSON (eg for Adapt-Contrib-Feedback, or to use one block and a text component as divider for the content)
  - Maybe create a list of example classes with all base colors?
    - Background: @primary-color, Color: @primary-color-inverted
    - Background: @secondary-color, Color: @secondary-color-inverted
    - Background: @tertiary-color, Color: @tertiary-color-inverted
    - Background: @quaternary-color, Color: @quaternary-color-inverted
- Page Hero Image (adapt_basic_presentation_01.jpg)
  - Full Width
  - Default Background Color: @background-color-inverted
  - Default Font Color: @foreground-color-inverted
  - Title and Body Text should be set via JSON
- Adapt-Contrib-Boxmenu (adapt_basic_menu.jpg)
  - Hero Image like Page Hero Image
  - Duration and Progress Indicator Position
  - Button Width
  - Position of Menu Items
- Adapt-Contrib-Slider (adapt_basic_question_01.jpg)
  - Range pointing down
- Adapt-contrib-gmcq (adapt_basic_question_01.jpg)
  - Change Layout when more than 2 items
  - Change Layout of Text to center
  - Remove Item Background Color
- Adapt-Contrib-Tutor (adapt_basic_question_02.jpg)
  - Max-Width for Text
  - Close Icon Position
- Adapt-Contrib-Hotgraphic (adapt_basic_presentation_01.jpg)
  - Change Image to width 100% so that image is stretched to full width?
- Adapt-Contrib-AssessmentResults
  - Make it pretty

### Implement Variables (Colors, Padding, Font):
- Navigation Bar
- Drawer
- Notify
- All Contrib Plugins
  - adapt-contrib-accordion
  - adapt-contrib-assessment
  - adapt-contrib-assessmentResults
  - adapt-contrib-blank
  - adapt-contrib-bookmarking
  - adapt-contrib-boxmenu
  - adapt-contrib-gmcq
  - adapt-contrib-graphic
  - adapt-contrib-hotgraphic
  - adapt-contrib-matching
  - adapt-contrib-mcq
  - adapt-contrib-media
  - adapt-contrib-narrative
  - adapt-contrib-pageLevelProgress
  - adapt-contrib-resources
  - adapt-contrib-slider
  - adapt-contrib-spoor
  - adapt-contrib-text
  - adapt-contrib-textInput
  - adapt-contrib-trickle
  - adapt-contrib-tutor
  - adapt-contrib-vanilla
