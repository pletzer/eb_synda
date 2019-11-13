# eb_synda

Easybuild recipe to compile synda on NeSI platforms

## Set up

```
export NESI_EASYBUILD_PROJECT_ID=<projectID>   ## e.g. nesi12345
module load project
```

## Download

```
git clone https://github.com/pletzer/eb_synda
```

## Build

```
cd eb_synda/mahuika

# now build
eb Synda-3.10-gimkl-2008b.eb --robot --force
```

## Load

```
module load Synda/3.10-gimkl-2008b
```

## Appendix

If you want to learn about creating your own modules

https://support.nesi.org.nz/hc/en-gb/articles/360000474535-Installing-Third-Party-applications
