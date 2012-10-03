CI_BASE
=======

Overview:
=========
CodeIgniter 2.1.2 with extra vars added. To be used for code completion purposes ONLY and NOT as the primary framework.

NOTICE: 
=======
Do not use this repo as a CI framework. The variables added will cause your configured DB object to be reset, among other things, and you will get errors.

Description:
============
Many IDEs will not support code completion for CI. Clone this repo and include it in the buildpath of your project for code completion to work.
There is also a variable included for a Facebook object if you are developing an FB app using CI. The libraries for the FB api are NOT INCLUDED here (see NOTE below), you would add those under your application libraries and code completion for the Facebook API should automatically work.

The following files are changed from the code CI 2.1.2:
=======================================================
user_guide/ - Removed
system/core/Controller.php - Modified
system/code/Model.php - Modified

NOTE: 
=====
Another repo exists containing the structure for a basic facebook app using CI (v2.1.2), Facebook PHP SDK (v.3.2.0) and H5BP (v4.0.0). Feel free to clone and begin using.
REPO: https://github.com/TheMakboul/CI_H5BP_FB  
