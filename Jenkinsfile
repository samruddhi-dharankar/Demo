pipeline 
{
	 agent any 
	 
	 stages 
     {
		stage("compile") 
        {
			steps 
            {
				echo "Compiling"
				bat """ javac Demo.java """
			}
		}
			
		stage ("run") 
        {
			steps 
            {
				echo "Running"
				bat """ java Demo"""
			}
		}
			
	}
}
