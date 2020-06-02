# MDH-MT-Template-Latex-EN

This is the Master Thesis Template for the Master Degree Programme Digital Healthcare at St. Pölten University of Applied Sciences.

It was originally created by [P. Lechner](https://github.com/hrtlacek) as [St. Pölten UAS Master Thesis Template](https://github.com/hrtlacek/ThesisTemplate-FH-StP) in 2015.  

In 2016, it was adapted by M. Wagner and K. Blumenstein to fit the needs of the St. Pölten UAS IC\M/T - Institute of Creative\Media/Technologies.

Furthermore, it was rarely used as a Master Thesis Template in the Master Degree Programmes Digital Healthcare and Digital Media Technologies.

In 2020, it was updated by [M. Andorfer](https://github.com/andorfermichael) including fixes and features to be properly usable again as a Master Thesis Template in the Master Degree Programme Digital Healthcare.

# Change Log
All notable changes to this project will be documented below.

The format is based on [Keep a Changelog](http://keepachangelog.com/).

## 2020-06-02 ([M. Andorfer](https://github.com/andorfermichael))
### Added
- Tables:
  - added packages and examples for multi-column and multi-page tables
- Preface and Dedication:
  - added examples for preface and dedication
- Listings:
  - added configuration for C#

### Changed
- Tables:
  - changed table caption to be left-sided

### Fixed
- Page Numbering:
  - fixed romanian count to be consistent
  - fixed arabic count to be reversed (left, right)
  - fixed header for main chapters

## 2020-03-05 ([M. Andorfer](https://github.com/andorfermichael))
### Added
- Sub-Sub-Section in text and list of contents (e.g. 1.1.1.1)

### Changed
- None

### Fixed
- None

## 2020-03-01 ([M. Andorfer](https://github.com/andorfermichael))
### Added
- Abbreviations list and examples
- Example of including pdf files directly into the appendix

### Changed
- Title Page
  - replaced German MT logo with neutral FH logo
  - replaced cyan with black color
  - improved wording
- Page Layout
  - changed page margins
  - implemented twoside layout
    - adaptive margins (bindingmargin)
    - adaptive headers (chapter title)
    - adaptive footers (page number)
    
### Fixed
- Font
  - added missing font declaration file for arial
  - fixed commands order so that the font is actually applied correctly
- Bibliography
  - removed outdated package natbib and replaced it with package biblatex to allow easy changes between citation styles (currently apa and ieee)

