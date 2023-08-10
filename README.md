while read file; do
    export "$file";
    done < .env