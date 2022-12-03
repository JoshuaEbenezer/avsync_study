# Score analysis

1. Run `create_sureal_format_database.py` to prepare the scores for sureal.
2. Run 
    `sureal --dataset ./avsync_surealformat.json --models P910 --output-dir ./sureal --plot-raw-data --plot-dis-video --plot-observers` 
    from the command line. Scores will be written to `./sureal`.
3. Run `surealscores_to_csv.py` to convert the sureal output to a csv file.