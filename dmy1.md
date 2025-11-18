# YANG Highlighting Demo

Below is a YANG example highlighted by GitHub:

'''yang

module example-module {
    yang-version 1.1;
    namespace "http://example.com/example-module";
    prefix ex;

    organization
        "Example Corp.";

    description
        "A minimal YANG module for testing GitHub syntax highlighting.";

    container config {
        description "Top-level configuration container.";

        leaf enabled {
            type boolean;
            default true;
            description "Enable or disable the feature.";
        }

        leaf hostname {
            type string;
            description "A simple string leaf.";
        }
    }
}
