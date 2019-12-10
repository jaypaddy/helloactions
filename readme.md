az ad sp create-for-rbac --name "hacker6helloworld" --role contributor \
                            --scopes /subscriptions/4fd85f80-d7c8-46d0-9b86-ba3b7402377a/resourceGroups/hacker6_helloworld/providers/Microsoft.Web/sites/hacker6helloworld \
                            --sdk-auth
