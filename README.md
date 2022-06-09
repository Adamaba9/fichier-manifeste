README.md

  ##
   1 creer une image docker sur notre register interne
      docker pull freemanpolys/catalogue-dsi:latest

      docker images

docker tag  freemanpolys/catalogue-dsi  registry.tools.orange-sonatel.com/coe/freemanpolys/catalogue-dsi:latest
      

      docker push registry.tools.orange-sonatel.com/coe/freemanpolys/catalogue-dsi:latest
      
      
      oc project pour se situer 


   2 creer des ressources 
        -config(configMap,secret)
        -pod
        -route ==> public
        -service   