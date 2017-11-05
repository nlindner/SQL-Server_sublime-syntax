# SQL syntax highlighting (SQL Server only) with sublime-syntax #

This draws from [Sublime HQ's SQL syntax](https://github.com/sublimehq/Packages/tree/master/SQL), [my original fork of tosher's TSQLEasy](https://github.com/tosher/TSQLEasy), and
[Dridus's Transact-SQL syntax](https://github.com/Dridus/Transact-SQL.tmbundle). I started by comparing these and other .tmLanguage SQL syntaxes, but limited the keywords to what is allowed by SQL Server. This is now written using Sublime Text's new .sublime-syntax. This works with SQL Server's default of enclosing all object names with square brackets, although it includes the brackets in the name (not sure how to recognize the same entity name either with or without brackets). 
  - Note that the SQL (override default) subdirectory is designed as a VERY minimal style syntax (with block-comment, string_interpolation, and strings repositories that other style-definitions can call) to override Sublime's default SQL package. 

If you have any syntax highlighting problems, please don't hesitate to submit an issue with sample code.