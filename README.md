# Ghormoon's helm repo

## zabbix-helm-chrt

Packaged from https://git.zabbix.com/projects/ZT/repos/kubernetes-helm/browse because they don't package it in a way that would allow to helm pull/install without manually cloning a repo, which breaks my ansible flow.

## openebs-zfs-storageclasses

Minimal chart that deploys storageclasses for openebs zfs-localpv for both containers and zvols. [ghormoon/kube-charts](https://github.com/ghormoon/kube-charts).

## metallb-l2advertisemet

Minimal chart that deploys L@Advertisement for metallb. [ghormoon/kube-charts](https://github.com/ghormoon/kube-charts).

## tigera-operator

packaged master while waiting for 3.27.3 release. will be deleted when upstream repo has fixed version, as 3.27.2 doesn't work for me

