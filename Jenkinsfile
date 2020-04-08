def target_node='SlaveNode'
pipeline { 
    agent {label "${target_node}"}	
        stages {
            stage('Build Stage') {		
                steps {               
                    echo "from Build Stage"              
					}
            }		
    
            stage('Deploy Stage') {
                steps {
                    echo "From Deploy Stage "
                                    
                    }                              
                }
    }
}
