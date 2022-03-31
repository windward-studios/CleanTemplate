# CleanTemplate
Running this tool will make changes to your template such as fixing expressions, or helping by upgrading any code changes between versions

## Usages
 Options are:  
        *-ps* Substitution parameter mode.  
        *-pp* Parameter Plus parameter mode. This is the default.  
        *-po* Parameter Only parameter mode.  
        *-sq* Smart quote - remove quotes around ${vars}. This is the default.  
        *-ru* Remove Unused styles, etc. This is the default.  
        *-tt* Text tags.  
        *-tf* Field tags (macro in Excel).  
        *-tp* Field Plus tags (macro in Excel). This is the default.  
        *-tc* Content Control tags (macro in Excel.)    
          
  Datasources are:  
        *-xml:name_of_datasource*  
        *-sql:name_of_datasource*  
  
  Full usage:  
      *[Options] [Datasources] template_file(s) output_directory*
