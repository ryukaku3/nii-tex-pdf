### nii-tex-pdf

#### repo file.
    # vi /etc/yum.repo.d/nii-tex-pdf.repo

####
    [tex-pdf-git]
    name=CentOS-$releasever - tex-pdf
    baseurl=https://ryukaku3.github.io/tex-pdf/
    enabled=0
    gpgcheck=0
    #gpgcheck=1
    #gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-CentOS-7

#### yum
    # yum --enablerepo=nii-tex-pdf search nii-
    # yum --enablerepo=nii-tex-pdf install nii-Tex-pdf
