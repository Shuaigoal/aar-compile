# aar-compile
apply aar from module's module

## In lib module build.gradle, Add flatDir in android{}

    repositories {
            flatDir {
                dirs 'libs'
            }
        }
        
## In main project module's build.gradle, Add flatDir too with detail path
  
    repositories {
          flatDir {
              dirs '..\\..\\LivingProject\\lib_common\\libs','libs'
          }
      }
      
## pictures

