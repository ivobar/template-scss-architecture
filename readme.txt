This skeleton for future projects implements the 7-1 sass architecture (could be used with any other preprocessor, of course!).

The purpose of each folder in the ./sass directory is the following:

--abstracts - all sass files that dont generate into css - eg mixins and variables.
--base - for basic product definitions.
--components - all styles for components, placed in individual files.
--layout - here we define certain layouts for the project - again in separate files.
--pages - here we put styles for specific pages of the project.
--themes - styles related to different visual themes.
--vendors - all third party styles come here (fonts etc.).

All styles should be partial sass files which are ultimately grouped and imported in the main sass file, which is then compiled in the styles css.