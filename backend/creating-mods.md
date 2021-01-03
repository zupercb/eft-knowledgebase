Mods Structure

Author-ModName-Version 	┓
			┃
			┣ ScriptFolder
			┗ mod.config.json
Folder structure is mostly depending on mod creator the most important file is a mod.config.json everything else depends how mod creator will structure it a Main Mod folder name need to contain Author ModName and a version as such Author-ModName-Version Example:

TheMaoci-ExamineAll-1.0.0

mod.config.json Structure

{
	"name": "ExamineAll",
	"author": "TheMaoci",
	"version": "1.0.0",
	"license": "MIT",
	"src": {
		"src/ScriptToLoad_1.js": "TamperModLoad",
		"src/ScriptToLoad_2.js": "CacheModLoad"
	}
}
there are 2 types of Loading types for the scripts you have located in src in mod.config TamperModLoad -> this loads just before starting the of the server so all variables are already loaded in. CacheModLoad -> this loads just after cacheing is done

Structure of script:

exports.mod = (mod_info) => {  
 // Sript goes here  
 // mod_info contains everything that mod.config.json contains as an object  
}  
