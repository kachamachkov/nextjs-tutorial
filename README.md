# nextjs-tutorial

## Routes notes

- Your file and folder structure determines the routes (convention over configuration)
- 404 in the box
- No need to install a router with code
- Nested routes? - just nest folders
- Dynamic routes? [] dynamic segment
  - Use params prop to access the ID
- Nested dynamic routes?
  - dynamic segments in the folder names
- Catch all segments?
  - Use slug
- Not found custom page
  - naming
  - custom not found and limiters for params inside folder structure
- Folder colaction
  - Colacation - project files can be safely colocated inside route segments, use export default to include them
  - Preference is to create another folder withing APP, like components
  - Private folders?(excluded from routing)
    - _ before name
    - separate UI logic from routing one
    - consistency while organizing internal files across a project
    - sort and group files in code editors
    - avoid naming conflicts with future next.js file conventions
- Route groups 
  - Utilize () to exclude the folder name from the url
- Layouts
- Nested Layouts
- Group layout