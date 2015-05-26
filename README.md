# RNAsnv_models
GBM models for RNAsnv

Consolidated model file for use in RNAvc configuration file can be found in releases section of RNAvc (https://github.com/bdownie/RNAvc/releases/latest)

File name | Edit class | R model name | Description
-------|--------|------- | ----------
Error.model | Variant call error | gbm.error.model | Error model (false positive variant call)
AtoI.model | A-to-I | gbm.ai.model | Human (B-lymphocyte) trained A-to-I model
Apobec1.model | C-to-U | gbm.apobec1.model | Mouse Apobec1 KO trained C-to-U model
Apobec2.model | C-to-U | gbm.cu.model | Human (B-lymphocyte) trained C-to-U model
