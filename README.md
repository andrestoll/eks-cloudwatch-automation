# eks-cloudwatch-automation

Small terraform repository that demonstrates how to automate cloudwatch dashboards, such they can be replicated for example, using terraform.

The easiest way to do it is to
1. create the dashboard in the console by hand
2. click on "Edit/View Source" and copy
3. Create a *.json.tmpl file and paste the json dashboard
4. Use the template file as the input to the dashboard resource and exchange and identifiers and names (check the *main.tf* file for reference)