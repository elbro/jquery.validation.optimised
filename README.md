# jquery.validation.optimised
jQuery Validation with performance optimisations for pages with a large number of inputs

For pages with a large number of inputs (typically > 100) jquery validate is very slow at parsing all the elements creating a UI hang on form submit. This version contains optimized parsing and error displaying functions which vastly improve the speed of validation without sacrificing any crucial functionality.

jquery.validate.unobtrusive.js has been modified to allow you to easily skip validation on a form. Useful if you are using a page with multiple long forms, simply add the "skipValid" class to a form..
