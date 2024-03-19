query run in tinker:
1. \App\Models\Book::where('title', 'LIKE', '%iusto%')->get();
2. \App\Models\Book::title('iusto')->get();   <!-- but not working :) -->
3. \App\ ... ->tosql

4. .\vendor\bin\phpunit <!-- for unit test -->


5. add limited for add review


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
