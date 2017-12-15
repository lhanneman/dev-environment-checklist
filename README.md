# dev-environment-checklist
my personal list of tools/apps/configuration when reformatting or setting up a new dev machine


# mac

# windows

git config (move to separate file)
located at C:\ProgramData\Git\

[core]
	symlinks = false
	autocrlf = true
	fscache = true
[color]
	diff = auto
	status = auto
	branch = auto
	interactive = true
[help]
	format = html
[rebase]
	autosquash = true
[diff]
	tool = vsdiffmerge
[difftool]
	prompt = true
[difftool "vsdiffmerge"]
	cmd = \"C:\\Program Files (x86)\\Microsoft Visual Studio\\2017\\Enterprise\\Common7\\IDE\\CommonExtensions\\Microsoft\\TeamFoundation\\Team Explorer\\vsdiffmerge.exe\" \"$LOCAL\" \"$REMOTE\" //t
	keepbackup = false
	trustexistcode = true
[merge]
	tool = vsdiffmerge
[mergetool]
	prompt = true
[mergetool "vsdiffmerge"]
	cmd = \"C:\\Program Files (x86)\\Microsoft Visual Studio\\2017\\Enterprise\\Common7\\IDE\\CommonExtensions\\Microsoft\\TeamFoundation\\Team Explorer\\vsdiffmerge.exe\" \"$REMOTE\" \"$LOCAL\" \"$BASE\" \"$MERGED\" //m
	keepbackup = false
	trustexistcode = true
