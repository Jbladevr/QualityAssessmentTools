# QualityAssessmentTools

## QualityAssessmentTools Extension for BlueJ

### Overview
The main goal of this extensions is to provide [BlueJ](https://bluej.org/) users the ability to check their code with code quality assessment 
tools. At the current stage QualityAssessmentTools extension provides Checkstyle that helps users of BlueJ write Java code that is following the coding standards.

### Requirements
[BlueJ](https://bluej.org/) 4.1.X running on JDK 8 or higher.

### Downloads
The latest version of the QualityAssessmentTools can be found [on the GitHub reposisitory](https://github.com/SoftwareExtensionRenovators/QualityAssessmentTools)
under QualityExtension.jar.

### Installation Instructions
* Download the latest [QualityExtension.jar](https://github.com/SoftwareExtensionRenovators/QualityAssessmentTools/blob/master/QualityExtension.jar)
* Place the jar file in BlueJ's extension directory.
  * For Windows or Unix:
  * Navigate to a BlueJ directory
  * While in the directory, place QualityExtension.jar in lib/extensions
* For Mac OSX:
  * Control+click BlueJ.app and choose Show Package Contents
  * Navigate to Contents/Resources/Java/extensions/
  * Place QualityExtension.jar in current folder
* **NOTE:** If you are upgrading from previous version of QualityExtension or have any Checkstyle extensions active, remove your current QualityExtension.jar and any of the Checkstyle.jar equivalents from the extension directory.

### How to use
1. In BlueJ, select **Quality Assessment Tool** from the **Tools** menu
2. Select **CheckStyle** from drop down menu
<br /> **NOTE:** The PMD option is currently under development.
