# rakeiora_get_data

[Rakeiora](http://rakeiora.ac.nz)

---
Data retrieval

---

Retrieve data (bams or vcfs, however you wish to 
define your inputs) from the Rakeiora sandbox.

This is for the case when you wish to just have some
test data to run through your workflows which are under
development.

Pull this repository into Rakeiora sandbox and define inputs
as you like: If you want some BAM (reads) data, define an
input that will prompt you for reads, single (or multi, if you want them)
normal (or tissue, if you want them), merged however
you want them.

Then do a test run. Rakeiora will prompt you for these
inputs and gather the ones that you select, merge them
as per your input definition(s), and put them into the resources
directory. This workflow will then move them into the
results directory. Since "results" is one of the directories that
is copied to your jupyter hub, you will have the datafiles
available to you there for download or other analysis.

Note that this workflow is unlikely to be approved for usage in
the Rakeiora portal, because it returns raw data to your
results directory.

But it may be helpful for you in workflow development.
