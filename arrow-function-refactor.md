Decided to refactor my code to use arrow functions instead of function declarations. I used this Regex, which seemed to handle everything in my codebase no problem (except for overload declarations, which is fine because they're unsupported on arrow functions.) This Regex is offered as-is, with no guarantees of  
Regex: (async )?function (.*)(\(.*\))(: .*)? \{  
Replacement String (VSCode): const  =  => {  
