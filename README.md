# devops-netolog
Next files will be ignored for terraform: 

	1. # **/.terraform/*
		
		Ignore all files in .terraform directories for all directories and subdirectories
		
	2. # *.tfstate *.tfstate.*

		Ignore: 1. All files with *tfstate extentions 2. all files with *.tfstate.* extention (for example, 123.tfstate.xyz)

	3. # crash.log crash.*.log

		Ignore all files with "crash.log" name
		Ignore all files which start with "crash" and have ".log" and have any characters between them (for expample, crash.123.log, crash.xyz.log)

	4. # *.tfvars
		
		Ignore all files with "tfvars" extentions

	5. # override.tf override.tf.json *_override.tf *_override.tf.json

		Ignore file "override.tf"
		Ignore file "override.tf.json"
		Ignore all files which names contain\end in _override.tf (for example, 213213dsfdsf_override.tf)
		Ignore all files which names contain\end in _override.tf.json (for example, wqe21312_overrride.tf.json)

	6. # .terraformrc terraform.rc
		Ignore file ".terraformrc"
		Ignore file terraform.rc

	
