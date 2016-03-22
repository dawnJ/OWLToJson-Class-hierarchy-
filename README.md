# OWLToJson-Class-hierarchy-
This main  function  of the code is to transform OWL class into JSON format.

Json format：
{
  "name":"<name>",
  "children":
    [
      {
        "name":"<name>",
         "children":
          [
            {"name":"<name>",<null or children array>},
            {<the same as above...>}
          ]
      }
    ]
}

Use Java language and Jena Library parser OWL document and transform to above JSON file format.
