Cassie Nguyen README File!

Answers for the questions

Widget Tree. Draw or describe the widget tree of your In-Class 01b app, at least four levels deep. If a future employer asked you to add a fifth tab, which single node in your tree would you need to change first, and why does that node "own" the number of tabs? Widget Tree


Stateless vs. Stateful. Pick one widget in your app that is stateless and one that is stateful. Explain, in plain language, what would break (or simply become unnecessary complexity) if you swapped which type each one was. Stateless vs. Stateful


Controllers & Lifecycle. Imagine you shipped this app to the App Store without calling _tabController.dispose(). Describe, step by step, what would happen in memory over hours of real-world use, and why a code reviewer at a real company would flag this immediately. Controllers & Lifecycle


Declarative UI. Compare the declarative approach used in Flutter (setState() → rebuild) to an imperative approach you may have seen elsewhere (e.g., manually changing an HTML element with JavaScript). Which would be easier to maintain in a large team, and why? Declarative UI


Team Collaboration. Reflect on setting up your shared GitHub repository with your partner: what part of the workflow (branches, pull requests, merge conflicts, or communication) felt hardest, and what would you do differently on your very first day at a new software job to avoid that friction? GitHub Teamwork


Restoration Layer. The starter code uses a RestorableInt tabIndex field and RestorationMixin instead of relying on setState() alone. Describe a real scenario (e.g., the OS killing your app in the background) where this extra layer matters, and what the user would experience if it weren't there. Code Deep-Dive


Listener → setState. In initState(), _tabController.addListener(() { setState(() { tabIndex.value = _tabController.index; }); }) connects the controller to the rest of the UI. If you deleted only the setState() call but kept the line updating tabIndex.value, would the visible tab still change when tapped? Explain why, tying your answer back to the Declarative UI idea above. Code Deep-Dive


One list, two loops. Both the TabBar's tabs: and the TabBarView's children: are built with a for (final tab in tabs) loop over the same tabs list. In your In-Class 01b build, did you keep this loop pattern or write out each tab/child by hand? Which approach is less likely to cause the "tabs[i] and children[i] don't line up" bug the 01b instructions warned about? Code Deep-Dive


Requirements → code. Reopen inclass01b.html and pick one required widget you added (AlertDialog, TextField, SnackBar, or ListView/Card). Point to the exact layer from the Concepts page's code walkthrough (e.g., "Layer 7 · Declarative build") where that widget lives, and explain why it belongs at that layer and not, say, inside initState(). Code Deep-Dive

a