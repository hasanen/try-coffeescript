guard 'haml',
      :haml_options => { :escape_attrs => false },
      :run_at_start => true,
      :input        => 'source',
      :output       => '.' do
        watch %r{^source/.+(\.haml)}
      end

guard 'sass',
      :input        => 'source/stylesheets',
      :output       => 'stylesheets',
      :all_on_start => true,
      :debug_info   => true,
      :line_numbers => true

guard 'coffeescript',
      :input        => 'source/coffeescripts',
      :output       => 'javascripts',
      :source_map   => false,
      :all_on_start => true
