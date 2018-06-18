
## Data Source:https://snap.stanford.edu/data/egonets-Gplus.html

1) Download: **gplus_combined.txt.gz**	Edges from all egonets combined
2) Load into Pandas: test_df = pd.read_table(r'C:\ ......\gplus_combined.txt.gz', compression='gzip', sep=' ',header = None, error_bad_lines=False).drop_duplicates()
