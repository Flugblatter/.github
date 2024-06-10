Organization for processing and presenting data of the Flugblätter/Todesurteile project.

Repositories:
* [flugblaetter_data_export](https://github.com/Flugblatter/flugblaetter_data_export): Fetches the raw data from GitLab, processes it, and outputs the results to
* [flugblaetter_data_ouput](https://github.com/Flugblatter/flugblaetter_data_ouput) (private)
* Based on these cleaned and processed data, [flugblaetter_static](https://github.com/Flugblatter/flugblaetter_static) builds a static webpage, which gets published [on GitLab](https://acdh-ch.pages.oeaw.ac.at/todesurteile/flugblaetter-static-page/) (private).
* To provide an advanced search tailored for linguistic needs, [flugblaetter_nosketch](https://github.com/Flugblatter/flugblaetter_nosketch) creates and publishes a NoSketch container (public!) based on the (test) data from [flugblaetter_data_ouput](https://github.com/Flugblatter/flugblaetter_data_ouput), which is made accessible on the static GitLab page.
