// Pipeline declarativo
pipeline {
    
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    // Fases
    stages {
        
        stage("Bulding") {
            
            // Passos de la fase
            steps {
                
                echo "Fase 1 - Paso 1";
                
            }
            
        }
        
        stage("Testing") {
            
            // Passos de la fase
            steps {
                
                echo "Test Unitarios...";
                echo "Test Integración...";
                echo "Test Aceptación...";
                
            }
            
        }
        
        stage("Fase 3 - Deploy") {
            
            // Passos de la fase
            steps {
                
                echo "Deploy artefacto!!!!";
                
            }
            
        }
        
    }
    
}
