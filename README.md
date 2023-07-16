# OSHW Certification Mark

This repository contains the design source files and prepared EDA files for the [Open Source Hardware Certification Mark](https://certification.oshwa.org/mark-usage.html).

If you just need an SVG or PNG file for your project, head to your [project page in the certification directory](https://certification.oshwa.org/list.html), you can download ready-to-go images with your project's UID from that page.

For more details on the Mark and its usage, see [the mark usage guidelines](https://certification.oshwa.org/mark-usage.html) and [license agreement](https://certification.oshwa.org/license-agreement.html).

## Design source files

Design source files are located under [`/sources`](./sources) in SVG format. Pre-made PNG files are also available.

## EDA files

Files for EDA software are located under [`/eda`](./eda). If you want to add new EDA files or update existing ones, see [contributing](#contributing)

## Contributing

We're happy to accept pull requests to add or update EDA files or alternative file formats for design programs. When you make your pull request, please include:

* The file format with a link to documentation on the format
* A list of programs which may edit this format, and their FLOSS license or approximate cost
* Any additional notes or tips on usage

We may request revisions or ask for additional details.

Note that due to how trademark law underpins the certification program, we can't accept changes to or allow derivative works of the mark itself.

## Changelog

**v2.6**

- Design modified for the final project UID structure, with two characters for the country code followed by six numbers.
- Wide (horizontal) design added
- KiCAD EDA files re-created

**v2.5**

- Project UID structure changed from six-character random alphanumeric to six-character with two country code letters followed by four numbers.

**v2.4**

- Initial public version

## License

Usage of the mark is covered by the OSHWA certification [license agreement](https://certification.oshwa.org/license-agreement.html).
