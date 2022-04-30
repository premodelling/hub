
<br>

* [The R Programming Language](#the_r_programming_language)
* [Linux](#linux)
* [References](#references)
  * [Papers](#papers)
  * [Articles](#articles)

<br>
<br>
<br>

## The R Programming Language

<br>

[The Comprehensive R Archive Network](https://cran.r-project.org)
* [Packages](https://cran.r-project.org/web/packages/index.html)
* [Basic Web Appilications via Shiny](https://cran.r-project.org/web/packages/shiny/index.html)
* [Financial Time Series Objects](https://cran.r-project.org/web/packages/timeSeries/index.html)

<br>

[R Manuals](https://cran.r-project.org/manuals.html)
* [Reference Index](https://cran.r-project.org/doc/manuals/r-release/fullrefman.pdf)
* [Interals](https://cran.r-project.org/doc/manuals/r-release/R-ints.pdf)
* [Laguage Definition](https://cran.r-project.org/doc/manuals/r-release/R-lang.pdf)
* [Writing Extensions](https://cran.r-project.org/doc/manuals/r-release/R-exts.pdf)
* [Installation & Administration](https://cran.r-project.org/doc/manuals/r-release/R-admin.pdf)
* [Import/Export](https://cran.r-project.org/doc/manuals/r-release/R-data.pdf)
* [Introduction](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)

<br>

[Intelligent Data Analysis Lab](https://s2.smu.edu/IDA/)
*  [stream](https://cran.r-project.org/web/packages/stream/index.html)


<br>
<br>
<br>


## Linux

<br>

Root

* https://www.tecmint.com/disable-root-login-in-linux/
* https://www.linuxfordevices.com/tutorials/linux/enable-disable-root-login-in-linux


Is SSH running?

```shell
	ps aux | grep sshd
```

<br>
<br>

### Installations

**Brave**

```bash
  sudo zypper install brave-browser
```
<br>

**IntelliJIDEA**

[Installation Guide](https://www.jetbrains.com/help/idea/installation-guide.html)

```bash
  sudo tar -xzf idea....tar.gz -C /opt
  /opt/idea-IC-213.7172.25/bin/idea.sh
```

<br>

**Docker**

https://en.opensuse.org/Docker
https://docs.docker.com/engine/reference/run/
https://docs.docker.com/engine/install/sles/
zypper addrepo https://download.docker.com/linux/sles/docker-ce.repo

<br>

**Docker Compose**

[About](https://docs.docker.com/compose/cli-command/)
[Usage](https://docs.docker.com/engine/reference/commandline/compose/)

```bash
  # -p: recursively
  mkdir -p docker/cli-plugins

  # unload
  curl -SL https://github.com/docker/compose/releases/download/v2.2.3/docker-compose-linux-x86_64 -o /usr/local/lib/docker/cli-plugins/docker-compose
  chmod +x /usr/local/lib/docker/cli-plugins/docker-compose
  
  sudo ln -s /usr/local/lib/docker/cli-plugins/docker-compose /usr/bin/docker-compose
```

and

```bash
  sudo docker-compose up
  sudo docker-compose stop
```

<br>
<br>
<br>

## References

<br>

### Papers

* [Model building and assessment of the impact of covariates for disease prevalence mapping in low-resource settings: to explain and to predict](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2021.0104#d1e945)

* [Predictive Model Assessment for Count Data by Claudia Czado, Tilmann Gneiting, Leonhard Held](https://doi.org/10.1111/j.1541-0420.2009.01191.x)

<br>

### Articles

* [AI, Mathematics & Global Diplomacy](https://www.theguardian.com/technology/2021/oct/15/ai-and-maths-to-play-bigger-role-in-global-diplomacy-says-expert)

* [Daniel Hallen, Digital Techology, NHS](https://healthcareglobal.com/interviews/daniel-hallen-nhs-england-and-nhs-improvement)

<br>
<br>
<br>
<br>

<br>
<br>
<br>
<br>