
[Using `rm` Safely](#rm)

> ## Using `rm` Safely
>
> What happens when we type `rm -i thesis/quotations.txt`?
> Why would we want this protection when using `rm`?
>
> > ## Solution
> > ```
> > $ rm: remove regular file 'thesis/quotations.txt'?
> > ```
> > {: .language-bash} 
> > The -i option will prompt before every removal. 
> > The Unix shell doesn't have a trash bin, so all the files removed will disappear forever. 
> > By using the -i flag, we have the chance to check that we are deleting only the files that we want to remove.
> {: .solution}
{: .challenge}
