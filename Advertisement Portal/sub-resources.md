### Sub-resources
* Sub resources is a resource which is depends on a main resource
* Sub resource cannot exists without resource
* Example: 
	* We have a post(in social media) resource and we have a comment feature on it.
	* here comment is the sub-resource
	* GET | http:localhost:8080/{resource}/{id}/{sub-resource}
