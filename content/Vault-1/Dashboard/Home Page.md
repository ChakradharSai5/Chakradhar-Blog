---
cssclasses:
  - dashboard
  - dashboard-ReadLineLength
---

### Knowledge Hub
- [[1 My Joyful Interests]]
- [[2 Functional Notes]]
- [[3 Library]]
- [[9 Systems and Standards in Place]]
---
### Time Capsule
- **1 Just Journals**
	- **Snap Journals**
		- [[30th Jan 2024]]
	- **Trip Journals**
		- [[Trip to Chandragiri from Kaniha in Feb 2024]]
- **2 Planner Journals**
	- **Finance Planner Journals**
		- [[Finance Plan Ideas]]
	- **Health Planner Journals**
	- **Trip Planner Journals**
- **TMS Planner Journals**
	- **Fortnight Planner Journals**
		- [[3 Feb Second Fortnight]]
		- [[4 Mar First Fortnight]]
		- [[5 Mar Second Fortnight]]
		- [[6 Apr First Fortnight]]
		- [[7 Apr Second Fortnight]]
	- **Long Term Planner Journals**
---
### Effort Logs
- **Projects**
 `$=dv.list(dv.pages('"3 Effort Logs/Projects"').sort(f=>f.file.name,"desc").limit(20).file.link)`
- **Spheres of Activity**

---
# Check
- 🗄️ Recent file updates `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(5).file.link)`
- 🔖 Tagged: pending `$=dv.list(dv.pages('#pending').sort(f=>f.file.name,"desc").limit(5).file.link)`
- 〽️ Stats
    - File Count: `$=dv.pages().length`
-  12 Rules of Life: `$=dv.list(dv.pages('"1 Knowledge Hub/3 Library/1 Books/12 rules of life"').sort(f=>f.file.name,"asc").limit(10).file.link)`