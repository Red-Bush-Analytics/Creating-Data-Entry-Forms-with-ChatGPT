
### Creating Data Entry Forms with ChatGPT


**General Disclaimer and Warning** <br>
As with all things ChatGPT and "AI" in general, the tools rely on information in the public domain for training. 
This information may or may not be accurate, and the training data sets may contain inaccurate information.  
The algorithms used by these tools are products of a human imagination and are complete with all of the human problems inherent in any model, including:
- Procedural (algorithm) biases included and excluded for all kinds of reasons, 
- Limited knowledge on the part of the developers,
- Limits on access to accurate data,
- Information exclusions due to copyright restrictions,
- Limits on physical storage and computing power, 
- Vested interests and agendas,
- How much you are willing to pay for the level of service,
- etc., etc., etc.<br>
  <br>

**It's your responsibility to verify all output to make sure it's suitable for your use.**<br>
If you are unsure whether the output is correct, seek help from someone with extensive experience in the field you are working in.<br> 


Creating a Data entry form with ChatGPT can help reduce the time to create new forms for projects. 
The chat prompts and outputs presented here are a short, basic demonstration of what can be produced.
The example included here creates two types of data entry forms,
- A metadata file for a borehole, and 
- A logging entry file for a borehole.
This output has various applications.  It could be used for individual logging and data entry per borehole or as an initial structure for constructing a database.<br>

**EXCEL IS NOT A DATABASE**  and it is not recommended to use it as such.  A collection of Excel files with metadata and logging is difficult to manage and expensive to convert into a format that can be imported into most types of modelling and data analysis software.
Do it right the first time, even for a small project? Create a SQL database using appropriate software; it's a bit of work, but your life will be easier in the long run.<br>

**The prompts.**<br>
The first prompt is very basic.  It is a request for a metadata sheet for an Iron Ore project.  This is a very generic approach, but it is a good way to start finding out what information is available.  Being too specific at the beginning risks a failed search or a poor result, as we do not know what data is available to the LLM.<br>
The result is for an Iron Ore project in the Northern Cape, South Africa.  ( Interesting! I did not specify a location. I assume the LLM has my IP address and correctly identifies me as being in South Africa when I generated the prompt.- I've run into my first bias issue!! beware).
The information listed looks reasonable, so I checked the Spreadsheet for the result.
The LLM makes further suggestions for improvements.  Please follow the prompts to view the changes I requested.
The spreadsheet in the dataset is the final result.

The files will need to be edited.  There are some fields (description/notes) missing; the standards list needs to be expanded, and your project may require additional (or fewer) fields in the logging, etc.
Please note that the LLM generates the named ranges for the dropdowns but does not create the links in the Excel files; these must be created manually.  It also creates the columns for graphics but does not create the graphs.

A similar process is followed for the logging sheet and codes.  You will need to edit the fields and links manually. You will need to create the graphics manually.

**Refinements**<br>
If there are specific fields that are required, you can give ChatGPT the list, and it will use these in creating the forms. If there are other requirements, add them to the prompt,  such as "create separate sheets for geology, RQD and Structure data ". If you have lists for dropdowns, these can be added.<br>

What you can do, the number of prompts, the amount of input data you can use and the type of result will depend on your subscription level (Free, Plus, Pro).

Time.  This process took about 3 hours, including verifying data and checking output. The files obviously need a lot more work to create well-formatted documents.  It does, however, help with the initial setup and making sure important fields are not omitted.
