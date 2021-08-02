## Usage
1. To access the Online3D viewer, go to https://machine-analytics.github.io/Online3DViewer/website/
2. Cick on "Open model from your device" and load the appropriate file you want to display from your local device. 
   (or)
   Click on "Open model from a url" and enter the appropriate url to display the 3D model.

## Get URL
The AWS project contains an S3 bucket named intel-point-cloud which stores zipped version of point cloud files (.ply)
Note: Ensure to store the files as <filename>.ply.zip
The AWS project has the IntelPointCloudDataAPI API Gateway that fetches files stored in S3 bucket intel-point-cloud. Use this url to fetch the file that you are interested in viewing. eg: https://py94ebm4ta.execute-api.us-west-2.amazonaws.com/test/pcd?file=hardware_tool.ply
  
