**v6.5.0** - August 7, 2019
- PR #148 - Asynchronous Fast rendering
- PR #157 - Added data-intersect-ignore property to node SVG to prevent intersection calculaton from selecting the wrong element.
- PR #159 - Resolved #158 - Add tooltip for edges

**v6.4.0** - July 11, 2019
- PR #145 - Fix 'Cannot read property 'getBBox' of null' error when remounting  (@ksnyder9801) - https://github.com/uber/react-digraph/pull/145
- PR #139 - Added eslint rules and fixed code. (@ajbogh) - https://github.com/uber/react-digraph/pull/139
- PR #136 - Add horizontal layotu engine (@wfriebel) - https://github.com/uber/react-digraph/pull/136
- PR #134 - Resolved #114 - maxTitleChars property is not being used (@thesuperhomie) - https://github.com/uber/react-digraph/pull/134
- PR #131 - Fix expected params in handleDragEnd test (@ksnyder9801) - https://github.com/uber/react-digraph/pull/131


**v6.3.0** - May 21, 2019
- PR #130 - Added code to return the d3 event on node selection (@ajbogh) - https://github.com/uber/react-digraph/pull/130
- PR #129 - Add panToNode/panToEdge imperative methods (@ksnyder9801) - https://github.com/uber/react-digraph/pull/129

**v6.2.0** - Feb 26, 2019
- PR #99 - Avoid creating orphan edges (@iamsoorena) - https://github.com/uber/react-digraph/pull/99
- PR #109 - Only import the expand icon (@rileyhilliard) - https://github.com/uber/react-digraph/pull/109
- PR #107 - Adding webpack-build-analyzer to react-digraph (@rileyhilliard) - https://github.com/uber/react-digraph/pull/107

**v6.0.0** - Jan 7, 2019 - Added mouse event to onCreateNode callback - Contributor: iamsoorena - https://github.com/uber/react-digraph/pull/98

**v5.1.0** - Nov 5, 2018 - Refactor of several APIs to fix race condition caused by using array indices to reference nodes rather than node IDs. Race condition would occur when a service would rewrite the array asynchronously, causing the indices to change. This would cause any node movement or edge changes to break.

**v5.0.6** - Oct 30, 2018 - First official release of v5.0 code. Please note that v4.x code is still present and being worked on, but it eventually be deprecated. Issues should include a version number to indicate to the developer which branch to work on. PRs should be targeted toward the correct branch (master is v5+, v4.x.x is older code).
