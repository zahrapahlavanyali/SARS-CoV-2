<template>
    <div>
        <div class="features">
            <h2 id="genomics" class="title">Genomics</h2>

            <div class="h-feature">
                <div class="h-feature-content">
                    <h3>
                        <RouterLink :to="'/genomics/global_platform/'">
                            Freely accessible ready to use global infrastructure for SARS-CoV-2 monitoring
                            <sup><font color="red">new</font></sup>
                        </RouterLink>
                        [<a href="https://doi.org/10.1101/2021.03.25.437046">bioRxiv</a>]
                    </h3>
                    <p>
                        Our system is specifically designed to encourage collaborative worldwide genomic surveillance to
                        rapidly identify and respond to emerging variants, its use of raw read data rather than
                        assembled genomes goes a step beyond current surveillance efforts. Specifically it enables the
                        coordinated worldwide surveillance of intra-patient minor AV frequencies: a distinction that
                        could yield decisive early-warnings of epidemiological conditions conducive to the emergence of
                        variants with altered pathogenicity, vaccine sensitivity or resistance. <br />
                        <a href="https://doi.org/10.1101/2021.03.25.437046">BioRxiv Preprint</a>
                    </p>
                </div>
                <div class="h-feature-focus">
                    <RouterLink :to="'/genomics/global_platform/'">
                        <img :src="$withBase('../img/gn.png')" />
                    </RouterLink>
                </div>
            </div>

            <div class="h-feature">
                <div class="h-feature-content">
                    <a href="https://covid19.galaxyproject.org/dashboard/">
                        <h3>Evolution</h3>
                    </a>
                    <p>
                        The list of selected sites in SARS-CoV-2 genome. It is continuously updated by the
                        <a href="http://datamonkey.org/">DataMonkey</a> team using GISAID data as it accumulates. This
                        list included all codons identified with <a href="http://datamonkey.org/fel">FEL</a> and
                        <a href="http://datamonkey.org/meme">MEME</a> methods to be evolving under positive or negative
                        selection.
                    </p>
                </div>
                <div class="h-feature-focus">
                    <a href="https://covid19.galaxyproject.org/dashboard/">
                        <img :src="$withBase('./img/evo.png')" />
                    </a>
                </div>
            </div>

            <RouterLink :to="'/artic/'">
                <div class="h-feature">
                    <div class="h-feature-content">
                        <h3>ARTIC: Amplicon based data analysis</h3>
                        <p>
                            A series of state-of-the-art workflows for the analysis of SARS-CoV-2 ARTIC data using the
                            Galaxy platform.
                        </p>
                    </div>
                    <div class="h-feature-focus">
                        <img :src="$withBase('../img/artic.png')" />
                    </div>
                </div>
            </RouterLink>

            <div class="h-feature">
                <div class="h-feature-content">
                    <h3>
                        <RouterLink :to="'/direct-rnaseq/'">
                            Analysis of SARS-CoV-2 transcription using Oxford Nanopore direct RNA sequencing
                        </RouterLink>
                        [<a href="https://doi.org/10.1101/2020.07.18.204362">bioRxiv</a>]
                    </h3>
                    <p>
                        We use direct RNA sequencing to precisely annotate the open reading frames and the landscape of
                        SARS-CoV-2 RNA modifications. Conservation of the RNA modification pattern during progression of
                        the current pandemic suggests that this pattern is likely essential for the life cycle of
                        SARS-CoV-2 and represents a possible target for drug interventions. We also provide Galaxy
                        workflows for the analysis of DRS data.
                    </p>
                </div>
                <div class="h-feature-focus">
                    <RouterLink :to="'/direct-rnaseq/'">
                        <img :src="$withBase('./img/drs.png')" />
                    </RouterLink>
                </div>
            </div>

            <div class="h-feature">
                <div class="h-feature-content">
                    <h3>
                        <RouterLink :to="'/genomics/no-more-business-as-usual/'">
                            No more business as usual - Agile and effective responses to emerging pathogen threats
                            require open data and open analytics
                        </RouterLink>
                        [<a href="https://doi.org/10.1371/journal.ppat.1008643">PLoS Pathogens</a>]
                    </h3>
                    <p>
                        In an age of digital connectedness, open, highly accessible, globally shared data and analysis
                        platforms have the potential to transform the way biomedical research is done, opening the way
                        to “global research markets” in which competition arises from deriving understanding rather than
                        access to samples and data.
                    </p>
                </div>
                <div class="h-feature-focus">
                    <RouterLink :to="'/genomics/no-more-business-as-usual/'">
                        <img :src="$withBase('./img/plos_p.png')" />
                    </RouterLink>
                </div>
            </div>

            <h2 id="cheminformatics">Cheminformatics</h2>

            <a href="https://www.biorxiv.org/content/10.1101/2021.03.17.435706v1">
                <div class="h-feature">
                    <div class="h-feature-content">
                        <h3>
                            Fast and accurate genome-wide predictions and structural modeling of protein-protein
                            interactions using Galaxy
                            <sup><font color="red">new</font></sup>
                        </h3>
                        <p>
                            Identifying interacting proteins reveals insight into living organisms and yields novel drug
                            targets for disease treatment. This is a publicly available, automated pipeline to predict
                            genome-wide protein-protein interactions and produce high-quality multimeric structural
                            models.
                        </p>
                    </div>
                    <div class="h-feature-focus">
                        <img :src="$withBase('../img/proteininteraction.png')" />
                    </div>
                </div>
            </a>

            <RouterLink :to="'/cheminformatics/'">
                <div class="h-feature">
                    <div class="h-feature-content">
                        <h3>
                            Docking simulations on the SARS-CoV-2 main protease.
                        </h3>
                        <p>
                            A Galaxy workflow for performing and evaluating molecular docking on a massive scale, based
                            on the set of fragment hits which are known experimentally to bind to the protein.
                        </p>
                    </div>
                    <div class="h-feature-focus">
                        <img :src="$withBase('./img/cheminfo.png')" />
                    </div>
                </div>
            </RouterLink>

            <RouterLink :to="'/proteomics/'">
                <h2 id="proteomics">Proteomics</h2>
                <div class="h-feature">
                    <div class="h-feature-content">
                        <p>
                            Galaxy workflows for analysis of Mass Spectrometry datasets from cell culture samples,
                            clinical samples and protein-protein interaction datasets as well as functionality for
                            performing metaproteomics analyses.
                        </p>
                    </div>
                    <div class="h-feature-focus">
                        <img :src="$withBase('./img/mspec.png')" />
                    </div>
                </div>
            </RouterLink>
        </div>
    </div>
</template>
<script>
export default {
    name: "home-features"
};
</script>
