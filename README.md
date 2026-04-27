# A* Truck Logistics Route Optimization

## Task 1: Read the attached A* Search Python code
The provided A* Search Python code was reviewed. The code was incomplete and contained several errors, including an incomplete graph, missing heuristic values, incorrect variable names, and syntax mistakes that prevented execution.

---

## Task 2: Identify and correct the bugs in the program
The following issues were identified and fixed:

- The graph was incomplete (only "Disaneng" was defined) → completed all nodes
- The heuristic dictionary was empty → added heuristic values for all locations
- The goal node was incorrect:
  - Changed from `" "` to `"Coligny"`
- Function name typo:
  - `simulte_path(pat)` → corrected to `simulate_path(path)`
- Undefined variables corrected:
  - `visit_order` → `visited_order`
  - `pat` → `path`
  - `tot_cost` → `total_cost`

---

## Task 3: Fill in the missing parts of the code
The missing components were completed as follows:

- Added full graph structure connecting all towns
- Added heuristic values for each node
- Corrected start and goal nodes
- Fixed the simulation function

---

## Task 4: Execute the corrected program

### Output:
Visited Order:
Disaneng → Mahikeng → Mmabatho → Slurry → Bakerville → Lichtenburg → Coligny

Optimal Path:
Disaneng → Mahikeng → Bakerville → Lichtenburg → Coligny

Total Cost:
110

---

## Task 5: Determine the optimal route

The optimal route from the start node to the destination is:

Disaneng → Mahikeng → Bakerville → Lichtenburg → Coligny

---

## Task 6: Answer the MCQs

- A* evaluation function:  
  f(n) = g(n) + h(n)

- Start node: Disaneng  
- Goal node: Coligny  
- Optimal path cost: 110  
- Algorithm used: A* Search Algorithm  

---

## Task 7: Submission

The following files are included in this repository:

- `astar_truck_route.py` → Corrected A* algorithm code  
- `README.md` → Answers and explanation  
- `output.png` (optional) → Screenshot of program execution  
