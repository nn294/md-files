# Setting up a static website with Azure Storage

## Pipelines `workflow definition`

> `trigger`: 1st line - indicates whether there are any triggers for this pipeline
> > `branches`: indicates the branch to use
> > > `include`: To be Expanded \
> > `paths`: To be Expanded \
> > > `include`: To be Expanded \
> > `batch`: To be Expanded \
> `name`: To be Expanded \
> `jobs`: To be Expanded \
> > Stages logical boundary within a pipeline; contains one or more jobs \
> > > `job`: runs on an agent; represents execution boundary for set of steps \
> > > > `displayName`: To be Expanded \
> > > > `timeoutInMinutes`: To be Expanded \
> > > `pool`: organized collection of agents \
> > > > `vmImage`: To be Expanded \
> > > `steps`: To be Expanded \
> > > > `checkout`: To be Expanded \
> > > > `task`: To be Expanded \
> > > > > `displayName`: To be Expanded \
> > > > > `inputs`: various input parameters that depend on the type of task \
> > > > > > `variable1`:  \
> > > > > > `variable2`:  \
> > > > > > `variable3`:  \
> > > > > > `variable4`:  \
> > > > `task`: To be Expanded \
> > > > > `displayName`: To be Expanded \
> > > > > `inputs`: various input parameters that depend on the type of task \
> > > > > > `variable1`:  \
> > > > > > `variable2`:  \
> > > > > > `variable3`:  \
> > > > > > `variable4`:  