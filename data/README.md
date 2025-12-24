# Data Folder

This folder is designated for storing datasets for your data analysis projects.

## Organization

You can organize your data files here in various ways:

- **By Project**: Create subdirectories for each project
- **By Data Type**: Organize by CSV, JSON, Excel files, etc.
- **By Source**: Keep data from different sources in separate folders

## Best Practices

1. **Document your data**: Include a description of each dataset
2. **Use clear naming conventions**: Use descriptive filenames (e.g., `sales_2024_q1.csv`)
3. **Version control**: Consider using Git LFS for large files
4. **Keep raw data**: Maintain original datasets separate from processed ones
5. **Add .gitignore entries**: Exclude very large files or sensitive data

## Example Structure

```
data/
├── raw/              # Original, unmodified datasets
├── processed/        # Cleaned and transformed data
├── external/         # Data from third-party sources
└── interim/          # Intermediate data transformations
```

## Notes

- Check the `.gitignore` file to see what file types are excluded
- Large binary files should be managed carefully in Git
- Consider using external storage or Git LFS for datasets > 100MB
